# J124 Final Project: Data Analysis of Tree Cover Loss
## By Heather Fergus
*This dataset was downloaded as a .csv file from Global Forest Watch*
## Data Analysis
### *Notes*
* The dataset notes there was a change in research model around 2011, which impacts comparing data from before 2015 with after 2015. Therefore, the data in this analysis will be filtered to only look at the years 2015 to 2021. 
* This dataset looks at total tree cover loss globally, but this doesn't just include deforestation. This could also be due to conservation efforts, wildfires, human and non-human causes of forest loss. 

#### Question 1: Which year had the highest total tree loss in hectares? Which had the lowest?
1. First I highlighted the data and created a new pivot table in the spreadsheet. 
2. Then I put “Tree_cover_loss_ha” in the values section, with “Year” in rows and filters, to filter for only 2015 to 2021. 
3. I sorted “Tree_cover_loss_ha” to summarize as SUM, as this will determine the total tree loss in that year. Also I sorted the “Year” to be descending by the “Tree_cover_loss_ha” as this will clearly display the highest amount first.
![Year With Most and Least Tree Loss](Question_1.png)

**_Answer: 2016 saw the highest total amount in tree cover loss globally at about 29,674,794 hectares, while 2015 saw the lowest amount globally at about 19,622,330 hectares._**


#### Question 2: (a) Which top five regions in 2016 and 2015 had the highest amount of tree cover loss? (b) How does this compare to the five countries with the highest tree loss each year from 2015-2021? 
#### (a)
1. First using the pivot table I filtered the “Years” column to only contain 2015 and 2016. 
2. I added the “Name” column to the Rows section and sorted this column as descending by the sum of “Tree_cover_loss_ha”. 

![Top Five Regions 2016](Question2a.png)
![Top Five Regions 2015](Question2aPic2.png)

**_Answer: In 2015 Canada appeared to have the highest hectares of tree cover lost, with over 2.7 million hectares, with Russia, the United States, Brazil, and Indonesia following. In 2016, Brazil became the highest region in tree cover loss at 5.3 million hectares, with Russia following close behind at just over 5 million hectares. This is a sharp increase of just under 3 million hectares in one year. Following these countries is Indonesia, the United States, and Canada._**

#### (b) 
1. To determine the top five regions of tree cover loss in each year I filtered the “Years” column in the pivot table once again to include years 2015 to 2021, and kept the other columns in the pivot table sections. 
2. Then I went through each year, determining the five countries with the most tree loss. 
3. For simplicity in the chart screenshot, since the top five regions each year all had above 1 million hectares in total loss, I filtered the tree cover loss to above 1 million hectares. 



**_Answer: Notably, the data shows that every year the United States, Russia and Brazil were always among the top five countries with the highest tree cover loss. Both 2015 and 2016 had the same five countries with the highest tree loss, and were the only two years in which Indonesia was listed as the top five. The United States has dropped below its tree loss levels in 2015 each year except for 2017, yet Russia and Brazil have consistently held higher levels than 2015 in each subsequent year._**


