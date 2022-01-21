# Rocket Fuel Case - # Heterogeneous Treatment Effects Analysis of Experiment Results
1. The case “Rocket Fuel: Measuring the Effectiveness of Online Advertising” is available for purchasing from the Harvard Business School case pack.  
2. For the analysis we are going to break down results by sub-groups depending on the number of times the individual was targeted for ads (tot_impr). I have created a data set called rocketfuel_deciles that you can use for this purpose. This simply takes the original rocketfuel data and adds a column labeling people into deciles (i.e., 10% groups) by tot_impr. (Note that when there are ties, different programs may break ties to put people into deciles differently. So my deciles won’t necessarily match yours, but should be similar).   
3. Summarize the variables in the data to familiarize yourself with them.    
4. Create a table to show the numbers and shares of individuals who were in the treatment vs. control group.   
5. Create a table of means and standard deviations and also graph histograms to check for balance in the variables that should not be affected by treatment across treatment and control.  
6. Plot the means and confidence intervals of the main outcome “converted” by control and treatment. Interpret the result and give a brief description of the confidence intervals, including noting whether one group has a higher or lower CI and whether that makes sense.   
7. Calculate and report the estimate of the Average Treatment Effect (ATE) of the ads for treatment relative to control, the associated standard error, and provide a 95% confidence interval on the Average Treatment Effects.   
8. Calculate the ATE again using the regression approach based on heteroskedasticy robust standard errors. Compare the results with the results in Q7.  
9. Create a summary table showing the sample size, the mean and the standard deviation of variables in the data set for both treatment and control group over the 10 deciles of total impressions.  
10. Next create a graph that shows the mean and 95% CI on “converted” separately for treatment and control plotted over the 10 deciles of total impressions.  
