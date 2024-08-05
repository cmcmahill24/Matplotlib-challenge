# Matplotlib-challenge
<<<<<<< HEAD
Module 5 Challenge
Analysis
- After analyzing the data in the following graphs, a couple of conclusions can be made. First, according to the pie chart section, the test subjects were almost 50/50 on male mice vs female mice. From this conclusion the study should not be affected on the sex of the mice since there were studied evenly on both sexes. Next, it seems that the drugs "Capomulin" and "Ramicane" had the most success with tumor shrinkage compared to the other drugs. In the dataframe and following boxplot graph in the "Outliers, Quartiles, and Boxplots" sections, these drugs preformed the best. For example in the final timepoint for the mice the tumor size for the placebo mice range from '65 to 72 (mm3)', while 'Infubinol' final tumor size ranges from '57 to 67 (mm3)', "Ceftamin" comes in a little better with ranges from '45 to 62 (mm3)' and finally "Ramicane" final tumor sizes range from '32 to 38 (mm3)' and "Capomulin" ranges from '28 to 38 (mm3)'. Capomulin and Ramicane's final tumor size is almost half the size of the competition drugs. Lastly, a fair conclusion to take from these data visuals is in the final visuals, scatterplots and correlations, the more the mice weigh the bigger the tumors are. You can see in the final visual the linregress model fits into the correlation.

Module 5 Challenge Resources

Xpert Learning Assistant (general debugging and coding help, bar plot using pandas: grouped_data = cleaned_df.groupby(['Drug Regimen', 'Mouse ID'])['Timepoint'].count().reset_index()
timepoints_per_regimen = grouped_data.groupby('Drug Regimen')['Timepoint'].sum()
timepoints_per_regimen.plot(kind='bar', figsize=(6, 5), rot=45)
plt.xlabel('Drug Regimen')
plt.ylabel('# of Observed Mouse Timepoints')
plt.show()
Pandas DataFrame (.rename and drop_duplicate codes)
Slack asktheclass (Summary statistic dataframe help, *Molly Fox & Jason Britton: summary_stats = cleaned_df.groupby("Drug Regimen").agg({"Tumor Volume (mm3)": ["mean", "median", "var", "std", "sem"]})
>>>>>>> eeda0d925cb22f07971265072e8886947d4a9606
