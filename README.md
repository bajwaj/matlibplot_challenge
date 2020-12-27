# The Power of Plots

## Prompt

What good is data without a good plot to tell the story?

So, let's take what you've learned about Python Matplotlib and apply it to a real-world situation and dataset:

While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

## Analysis Results

* Observation 1: There are four treatment types we were considered 'promising treatments': Capomulin, Ramicane, Infubinol, and Ceftamin. When we look at our first summary table we can see that the variance is highest to lowest: Ramicane, Capomulin, Ceftamin, Infubinol. You can see this ranking visually in the box plots with the sizes of the boxes. Respectivley, you can see that the standard deviation also increases as the variance increases. Meaning as the tumor volumes vary more widely the distance from the mean increases for all the tumor volume data for the given treatment. Specifically, Infubinol has the most variance and highest standard deviation of the four treatments. Later on we see in the graph there is an outlier with the value 36.83290494999999 outside the outlier boundary for Infubinol that maybe contributing to the increase in variance and standard devation.
* Observation 2: We were asked to take a look at one mouse treated with Capomulin. We can observe from the line plot overtime (looking at timepoints) Mouse B128's tumor volume decreased from 45.0 to 39.9 mm3 with Capomulin treatment. From my own scatter plot generated below the line plot you can also see a strong negative correlation. This means treating Mouse B128 with Capomulin has a strong correlation decreaing tumor volume.
* Observation 3: In the last portion of the homework we were asked to calculate the correlation coefficient between mouse weight and average tumor volume for the Capomulin regimen. The correlation coefficient was 0.84 and after examining the scatter plot we can conclude there is a strong positive relationship between mouse weight and average tumor volume for the Capomulin regimen. This means when mice in this study are treated with Capomulin theres a strong correlation that as their weight increases so does the average tumor volume.
