# Digital-Marketing-Analysis (Work-In-Progress)

## Enhancement Strategies for Digital Membership Card Adoption
### Project Introduction
In an era where digital access is king, this project seeks to unravel the patterns and behaviors influencing alumni engagement, specifically in the context of digital membership card downloads.

### Problem Statement
The project's analytical quest centers on discerning the variables that significantly impact the amount donated by alumni. This understanding aims to guide effective strategies to enhance digital card uptake.

### Methods and Tools
The project harnesses Python’s data-centric libraries: numpy for calculations, pandas for data structuring, and matplotlib and seaborn for visualization, to navigate and analyze the alumni dataset.

### Data Cleaning Insights
The initial phase of the data cleaning was a meticulous process, where we categorized ages into ranges for a more structured analysis and divided the country column into binary values to isolate the influence of domestic versus international alumni. While insightful, these initial transformations did not lead to the anticipated insights. Subsequently, we pivoted to emphasize actionable variables, such as adjusting membership categories to reflect actual engagement levels and refining the donor history variables to better capture the nuances of alumni giving behavior. For instance, we consolidated various donation amounts into cumulative figures to model the potential lifetime value of each alumnus.

### Key Findings
The linear regression analysis brought to light intriguing trends:

* Membership level, particularly Lifetime Membership, stood out in its correlation with donation amounts, though a negative correlation with New Graduate Fee suggested differing engagement levels.
* Gender showed marginal differences in donation behavior, with male alumni showing slightly more activity.
* A decision was made to exclude the Age variable due to its high correlation with Lifetime Membership, ensuring a more accurate model.

Cluster Analysis & Time-Series Analysis
* The cluster analysis identified distinct segments within the alumni, laying the groundwork for personalized engagement strategies.
* The time-series analysis offered a historical lens, showing donation amounts and patterns over the years. while the cluster analysis identified distinct segments within the alumni, laying the groundwork for personalized engagement strategies.

### What’s Next
Moving forward, the major research question - what drives an alumnus to download a digital membership card - will be tackled through logistic regression, seeking to pinpoint predictor variables for targeted marketing campaigns.

### Feedback Request
Your feedback or suggestions are highly valued to refine and advance this analytical journey. How can we make the digital leap more alluring to alumni? Share your thoughts.

*** Data Privacy Notice: Due to the sensitive nature of the real-time data used in this project, the full dataset has not been uploaded to GitHub to maintain the confidentiality and privacy of the information. The provided Jupyter notebook includes a preview of the data and outlines the analytical methods applied, giving a glimpse into the process while respecting data protection obligations. ***


