features
balancing


## Balancing the intensity classification model
In this model we are using four indicators that show the intensity. Those indicators are grouped into four category's. Light, Moderate, Hard and Very hard. Below you can see the unbalanced classification model and the results it gives. 

![Intensity_count_balanced](/Evidence/Data_preprocessing/Intensity_count_unbalanced.png)<br>
Intensity count plot

![Results intensity_count_balanced](/Evidence/Data_preprocessing/classification_report_unbalanced.png)<br>
Intensity results

![Results intensity_count_balanced](/Evidence/Data_preprocessing/cross_validation_report_unbalanced.png)<br>
Crossvalidation results

To balance the dataset, I have put everything inside one dataframe.

```
training_dataset = dataset[['sum_mag_of_acc', 'bmi','intensity','intensity_light', 'intensity_moderate', 'intensity_hard', 'intensity_very_hard']]
```

For the balancing I have used the functions resample and concat. To configure resample I have counted the current intensity Light with the following code.

```
print(training_dataset.intensity_light.value_counts())
```

Because of this, I knew I would need to resample everything to 268. With the following code:
```
df_intensity_light = training_dataset[training_dataset.intensity_light==1]
df_intensity_moderate = training_dataset[training_dataset.intensity_moderate==1]
df_intensity_hard = training_dataset[training_dataset.intensity_hard==1]
df_intensity_very_hard = training_dataset[training_dataset.intensity_very_hard==1]

df_intensity_moderate_upsampled = resample(df_intensity_moderate, replace=True, n_samples=268, random_state=123)
df_intensity_hard_upsampled = resample(df_intensity_hard, replace=True, n_samples=268, random_state=123)
df_intensity_very_hard_upsampled = resample(df_intensity_very_hard, replace=True, n_samples=268, random_state=123)

df_upsampled = pd.concat([df_intensity_light, df_intensity_moderate_upsampled, df_intensity_hard_upsampled, df_intensity_very_hard_upsampled])
```

Results:
- Very Hard    268
- Hard         268
- Moderate     268
- Light        268

![Intensity_count_balanced](/Evidence/Data_preprocessing/Intensity_count_balanced.png)<br>
Intensity count plot

![Results intensity_count_balanced](/Evidence/Data_preprocessing/classification_report_balanced.png)<br>
Intensity results

![Results intensity_count_balanced](/Evidence/Data_preprocessing/cross_validation_report_balanced.png)<br>
Crossvalidation results

Conclusion:
One of the flaws of up-sampling is that there is a big chance on overfitting. Below you can read the results of the regular test and the cross validation test. You can clearly see that it's overfitting and because of that the scores get lowered aswell!

https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/intensity_classification_model_BALANCED_DONT_EDIT.ipynb