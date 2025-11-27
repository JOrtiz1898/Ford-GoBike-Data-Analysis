Ford GoBike System Data Analysis

Project Overview

This project performs an exploratory and explanatory data analysis on the Ford GoBike System data (now known as Bay Wheels). The goal is to uncover behavioral differences between the two main user types: Subscribers and Customers.

The analysis focuses on trip duration, daily usage patterns, and weekly trends to determine how these groups utilize the bike-sharing service differently.

Dataset

The data consists of trip data for the Ford GoBike system. Each trip is anonymized and includes:

Trip Duration (seconds)

Start Time and Date

End Time and Date

User Type (Subscriber or Customer)

Member Gender

Member Birth Year

Start and End Station Information

Files in the Repository

This project is divided into two major parts:

Part_I_exploration_FINAL HTML.html

This document contains the exploratory data analysis (EDA).

It details the process of cleaning the data, univariate exploration (histograms, etc.), bivariate exploration (scatter plots, box plots), and multivariate exploration.

It documents the thought process and observations at every step of the analysis.

Part_II_explanatory_FINAL HTML.html

This document is a polished slide deck presentation of the major findings derived from the exploration phase.

It focuses on communicating specific insights with clean, explanatory visualizations.

Key Insights & Findings

The analysis revealed distinct behaviors between the two user groups:

Subscribers (Commuters):

Tend to have short, consistent trip durations (mostly under 20 minutes).

Usage peaks heavily during rush hours (8 AM and 5 PM) on weekdays (Mon-Fri).

This suggests "Subscriber" usage is primarily for commuting to and from work.

Customers (Casual/Leisure):

Take significantly longer rides compared to subscribers.

Usage peaks on weekends (Saturday and Sunday) and during midday hours.

This suggests "Customer" usage is largely recreational or for leisure activities.

Multivariate Analysis:

When combining user type, day of the week, and hour of the day, the data confirms that long durations are best explained by the combination of "Customer" status and weekend/midday time slots.

Tools Used

Python 3

Jupyter Notebook

Pandas (Data manipulation)

Matplotlib & Seaborn (Data visualization)

How to View

Since the notebooks have been exported to HTML, you can download the .html files and open them in any web browser to view the analysis and presentation.
