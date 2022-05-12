# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project is to figure out the outcome of Kickstarter projects based on their launch date and funding goal. The dataset consists of 4113 campaigns launched between August 2009 and May 2017. For analysis purposes the data was filtered to include only campaigns within the 'plays' category. There seems to be a connection between which month of the year the Kickstarter campaign was started for plays and its success, while the goal amount has a sort of cyclical relation to the success of the campaign for plays.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
In order to analyze the outcomes of Kickstarter campaigns for theater/plays, the number of successes, fails, and cancellations were plotted for each month in the following graph below:

![Theater Outcomes VS Launch] (/resources/Theater_Outcomes_vs_Launch.png)

As is seen in the graph above, campaigns started in May and other Summer Months succeeded more than campaigns started in Winter Months, 111 campaigns succeeded compared to 52 failures. The number of successes continue to fall off gradually throughout the rest of the year.

### Analysis of Outcomes Based on Goals
The next graph looks at the percentage chance of a successful, failed, and cancelled campaigns based on the goal set by the Kickstarter campaign. This data also focuses only on subcategory plays, rather than the parent category theater.

![Outcomes VS Goals] (/resources/Outcomes_vs_Goals.png.png)

As is seen in the graph above, the success rate of a campaign in the plays subcategory declines as the goal of a the campaign increases, up until $30000 - $44900 where it has a temporary increase. After that it immediately decreases to a very low rate of success. Additionally, as there are no cancelled Kickstarter campaigns in the plays subcategory, the failure rate and the success rate have an inverse relationship.

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on the analysis, a Kickstarter campaign within the theater category should be launched within the Summer Months, or more specifically within May, as this seems to be when most of the successful campaigns have been launched. However, this also could imply more competition and could lead to a less backers for any individual campaign.


- What can you conclude about the Outcomes based on Goals?
The goal of the campaign should be within the range of $0 to $19999, as after $19999 the campaign has a higher chance of failure than success.

- What are some limitations of this dataset?
The dataset does not take into account trends, or the nature of the campaigns being started. While it is categorized, it an analysis cannot be performed as to which of the campaigns appeal to the taste of the backers, and which of the campaigns are topical at the time of the launch. This is a limitation of the dataset as this could be a major contributing factor as to which campaigns succeed and which do not. Additionally, some Kickstarter campaigns can be promoted better than others, on social media and other forms of advertisement, that can contribute to the success of a campaign.

- What are some other possible tables and/or graphs that we could create?
Possible tables and graphs include:
  - Bar graph to show the categories and subcategories with the most success rate.
  - Line chart to show the total number of campaigns over the range of years, to see the growth of Kickstarter campaigns.
  - Bar chart to show the effect of a campaign being in the Spotlight on the Outcome of the campaign.
  - Bar Chart for Length of campaign vs Success of campaign.
