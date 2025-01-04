# Forage job simulation _ Accenture
This is where i documented my project from job simulation FORAGE under ACCENTURE

###Table of contents 
---
[Project overview](#project-overview)

[Data source](#Data-source)

[Tool used](Tool-used)

[Data description](#Data-description)

[Data field](Data-field)

[Data cleaning and preparation](#Data-cleaning-and-preparation)

[Exploratory data analysis](#Exploratory-data-analysis)

[Data visualization](#Data-visualization)

[Result](Result)

[Recommendations](#Recommendations)


### project overview
---
The primary goal of the social buzz dataset is to enable deeper insights into dynamics of social media,including trend ,sentiment,content strategy and user engagement.  
This dataset support applications like trend analysis, sentiment analysis, and brand monitoring, helping researcher and businesses make data-driven decision about activity.

### Data source
---
The three dataset (Reaction,Reaction type,Content) information was gotten from kaggle.

### Tool used
---
- Microsoft excel
- Power BI
- Github for portfolio 

### Data field
---
Content: 
- Content ID
- User ID
- Content type
- Category

Reaction:
- Content ID
- User ID
- Reaction type
- Datetime

Reaction type:
- Reaction type
- Sentiment
- Score

### Data cleaning and preparation
---
- Removal duplicates
- Removal of rows which values are missing
- Changing of datatype
- Removal of columns which are not relevant to the task

### Data modelling
---
working with multiple datasets, data modelling involves combining related information to create a unified structure for analysis. VLOOKUP was the used function in excel for merging the three dataset given with the common keys

### Exploratory data analysis
---
- Top 5 performing categories
- retrieve the count of category by sentiment
- calculate the sum of score per sentiment
- retrieve count of content type per month

### Data visualization
---
![accenture 2rrr](https://github.com/user-attachments/assets/96b64437-5f95-45da-a7e3-e5afbf13825a)

### Results
---
- A total of 24.57k content IDs were analyzed with 16 categories and 4 content types contributing to engagement
- 16 reaction types of reaction were recorded with significant activity in photos had the highest reaction count, followed closely by videos
- Positive sentiment dominates at 56.19%(13.81k), while neutral sentiment accounts for 31.30%(7.7k), and negative sentiment is the lowest at 12.5%(3.07k)
- The sum of chores by sentiment reveal a similar trend, with positive sentiment signficantly higher(85%)
- The top 5 reactions are super love,adore,want,cherish,and love, with super love leading at 114k score. these reactions highlight a strong positive emotional connection with the content
- Engagement fluctuates throughout the year with noticeable peaks in april and november, indicating these months had higher activity levels.
- Photos generate the most reactions, followed by videos and GIFs,suggesting that visual content drives engagement


### Recommendations
- Focus on positive content: Since positive sentiment is dominant,continue creating and promoting content that resonates emotionally with audiences
- Invest more in photos and video content, as they drive the highest engagement. optimize these formats for mobileband social platforms to maximize reach
- Use the insight from april and november to plan major campaigns,promotions or launches during these months to capitalize on audience activity
- Analyze the reasons behind the 12.5% negative sentiment and work to mitigate issues by addressing concerns or adjusting content strategies
- Introduce more interactive and relatable reaction options to diversify audience engagement 
- Keep an eye on shifts in reaction scores and sentiment throughout the year to adapt strategies dynamically.




