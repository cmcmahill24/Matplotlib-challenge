# Matplotlib-challenge
Module 5 Challenge Resources

Xpert Learning Assistant (general debugging and coding help, bar plot using pandas: grouped_data = cleaned_df.groupby(['Drug Regimen', 'Mouse ID'])['Timepoint'].count().reset_index()
timepoints_per_regimen = grouped_data.groupby('Drug Regimen')['Timepoint'].sum()
timepoints_per_regimen.plot(kind='bar', figsize=(6, 5), rot=45)
plt.xlabel('Drug Regimen')
plt.ylabel('# of Observed Mouse Timepoints')
plt.show()
Pandas DataFrame (.rename and drop_duplicate codes)
Slack asktheclass (Summary statistic dataframe help, *Molly Fox & Jason Britton: summary_stats = cleaned_df.groupby("Drug Regimen").agg({"Tumor Volume (mm3)": ["mean", "median", "var", "std", "sem"]})
