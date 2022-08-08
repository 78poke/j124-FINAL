# California Kindergarten Immunization Rates 2000 and 2014

# Summary 

In the 1998, The Lancet published a research paper that claimed that there was a connection between the MMR vaccine and Autism disorders. The paper was highly controversial and caused quite a stir as the lead author had financial conflicts of interest and allegedly manipulated the study data. The paper wasn't retracted until 2010, which was more than enough time for it to leave its mark on the future of not only MMR vaccines, but all vaccines in general.

This data analysis aims to take both a broad look at vaccination and exemption rates and a much more focused look on counties between the year 2000 and 2014. The vaccination rates from 2000 to 2014 has dropped and exemption rates have gone up. While taking a look at the top 3 counties in vaccination rates shows us that some areas weren't that heavily affected by this, the counties with the lower vaccination rates tell us a different story. 

The top 3 counties with the lowest vaccination rates are much more scattered. It's not the same recurring counties like it is for the high vaccination rates data. Taking a look at the lowest vaccination rates, you can see that there are drastic changes between the years 2000 and 2014. Some counties deal with a drop in vaccination rates, while just a few others experience a rise in vaccination rates. What could have triggered these drastic changes? Could it have to do with the Lancet paper for those counties that dropped? Or does it have to do with a change in political/religious beliefs in these areas? Does the area of these counties play a factor? For example, does a rural or modern area have better vaccination rates than the other? This data can only tell us so much, an in-depth analysis on these counties and the residents, laws, influences, and much more need to be explored. Focusing on those counties that have had drastic changes will be key to answering these questions as well as bringing up more.

# Sources
I analyized the [California Kindergarten Immunization Rates](https://www.kaggle.com/datasets/broach/california-kindergarten-immunization-rates?select=StudentData.csv) from the California Department of Public Health with a focus on the kindergarten immunization statistics. 

**Interview Contacts**
 
1. Glenda Deputy, School Board Seat B, President
* Email: glendajeanma@gmail.com
* Phone: 775-578-3777
* As one of the board members of the Humboldt School District, I believe they can gave a lot of information regarding why there has been a drastic decrease in vaccination rates for their kindergarteners. It'll be a great place to start with considering how low the vaccination rates have gotten and to see if it's a trend with other grades as well. 
2. Ramiro Moreno, President of San Benito School District
* Email: morenor@sbcisd.net 
* Another president of a school district that has seen a drastic change in vaccination rates. However, this school district has seen an increase in vaccination rates. Just like the Humboldt school district, this would be to a great contact to find out what has been done to get their rates up. With this contact, there'll be two sides of the stories being explored. 

**Additional Sources**

1. Senate Bill 277 in Humboldt County[Senate Bill 277 in Humboldt County](https://humboldtgov.org/DocumentCenter/View/54431/1---Vaccination---Implementation-of-Senate-Bill-277-in-Humboldt-County?bidId=)
* This document states how humboldt county has the fifth lowest vaccination rate and one of the highest personal belief exemptions rates in the state. 
* This document should bring up more questions onto why there aren't higher vaccination rates in the county, considering the chances of getting whooping cough, which are pretty high and can be fatal for children, as well. 
2. [Personal Beliefs Exemptions](https://fsi.stanford.edu/news/vaccination-rates-climb-california-after-personal-belief-exemptions-curbed)
* An article that could question/challenge personal belief exemptions. 
* It is stated how vaccines shouldn't be exempt as anybody afraid or cautious about them are misinformed. The facts and science behind vaccinations are enough to require people to have them. Will be interesting for counties that have high exemption rates. 
 # Data Analysis 

1. What were the immunization rates for the year 2000 and 2015? 

A pivot table with *Calculated Fields*  will be used to find the immunization rates. 

To add a *Calculated Field,* all you have to do is click Add 

<img width="277" alt="ADD" src="https://user-images.githubusercontent.com/88923290/183419495-f5a06300-7946-4939-bbc6-5b5244ae3e0a.png">

Then at the very top the *Calculated Field* option should pop up.

<img width="378" alt="custom field" src="https://user-images.githubusercontent.com/88923290/183419582-3c2767f5-f48e-47c8-85eb-0d2549544f3c.png">

From there, you can make formulas like the one before in order to get a desired outcome.

<img width="296" alt="j124 q1" src="https://user-images.githubusercontent.com/88923290/183418356-0bed40ff-768e-4a91-a291-8e9a417f223e.png">

Along with this, a filter for the years will need to be used as well. 

<img width="280" alt="j124 q1 filter" src="https://user-images.githubusercontent.com/88923290/183418549-6b2eb9ac-0753-4e93-9c5a-9fb3deb78042.png">

Clear all and select only the years 2000 and 2014.

<img width="329" alt="j124 q1 filter 2" src="https://user-images.githubusercontent.com/88923290/183418567-473aa6d5-f1e3-4de4-9014-040ebfd8039f.png">

> This filter and Calculated Fields will be used for future pivot tables as well. 

The Pivot Table should end up like this

<img width="450" alt="j124 q1 2" src="https://user-images.githubusercontent.com/88923290/183420150-a54d71bf-20e0-4aa7-89d2-47ef6fd054fa.png">

The vaccination rates for all three vaccines were higher in 2000 than in 2014. 

2. What were the exemption rates in 2000? 2014? 

A pivot table with *Calculated Fields* will be used once again. 

<img width="292" alt="j124 q2 3" src="https://user-images.githubusercontent.com/88923290/183421110-1314834f-8331-414f-b81e-fb8d14ca6834.png">

The pivot table should come out looking like this. 

<img width="348" alt="j124 q2 2 " src="https://user-images.githubusercontent.com/88923290/183421231-4d7a9122-4bba-4dee-a434-c391082c220b.png">

The exemption rates were higher in 2014 than in 2000, showing a correlation between higher exemption rates and lower vaccine rates in 2014 and higher vaccination rates and lower exemption rates in 2000. 

3. Which counties had the highest vaccination rates in 2000? 2014? 

The same *Calculated Fields* from q1 will be used for this pivot table, only thing new will be the addition of counties. 

<img width="553" alt="j124 q3 4" src="https://user-images.githubusercontent.com/88923290/183422564-b5603a12-92ca-457f-8122-14e576d4e22f.png">

In order to find the three counties with the highest vaccination rates, the *Order* needs to be set to *Descending* and *Sort By* will be adjusted for each of the three vaccination rate values. 
 
<img width="312" alt="j124 q3 5" src="https://user-images.githubusercontent.com/88923290/183422881-0cb5e450-29a7-4b31-b9f9-01f53f54284c.png">

MMR year 2000 

<img width="306" alt="nmmr 2000 q3 " src="https://user-images.githubusercontent.com/88923290/183424329-edd485c9-ac13-4a17-80fa-8ac3e7327408.png">

MMR year 2014

<img width="306" alt="j124 q3 2014 nmmr" src="https://user-images.githubusercontent.com/88923290/183424380-7bb001d8-e99b-43a3-8044-2142b9926209.png">

DTP year 2000

<img width="307" alt="ndtp2000 q3" src="https://user-images.githubusercontent.com/88923290/183424460-8786c5bd-e56d-4fd9-9d8a-39b376168503.png">

DTP year 2014

<img width="304" alt="j124 q3 nDTP 2014" src="https://user-images.githubusercontent.com/88923290/183424521-446a7eea-8291-472b-ba5f-6026fa8aa943.png">

Polio year 2000 

<img width="306" alt="npolio 2000 q3" src="https://user-images.githubusercontent.com/88923290/183424632-6c20026d-1876-4751-b649-d32f5e1634e5.png">

Polio year 2014

<img width="303" alt="j124 q3 nPolio 2014" src="https://user-images.githubusercontent.com/88923290/183424667-2654959f-d678-409e-8d90-0975f32a2464.png">

There are 4 counties, with all one recurring more than once. Yuba was constant in all data sets. 

4. Which counties had the lowest vaccination rates in 2000? 2014? 

A duplicate of the same pivot table used for question 3 can be used for this question. All that needs to be changed is *Order* from descending to acending.

<img width="286" alt="j124 q4 ascending" src="https://user-images.githubusercontent.com/88923290/183425746-0a85fef5-1401-4ae4-b18a-f2f4c383f222.png">

MMR year 2000 

<img width="303" alt="q4 nmmr 2000" src="https://user-images.githubusercontent.com/88923290/183425947-cd7cfb60-2a72-406c-a190-80a53c643769.png">

MMR year 2014 

<img width="305" alt="q4 nmmr 2014" src="https://user-images.githubusercontent.com/88923290/183425972-e1e500ac-1fb2-400f-877b-c40068724a47.png">

DTP year 2000

<img width="310" alt="j124 q4 year 2000 nDTP" src="https://user-images.githubusercontent.com/88923290/183426009-5ef3c705-210a-4502-981f-edc03ab813a3.png">


DTP year 2014

<img width="309" alt="j124 q4 year 2014 nDTP" src="https://user-images.githubusercontent.com/88923290/183426074-ef72f8a9-0ee7-4ae8-a5d2-6834a8b54537.png">


Polio year 2000

<img width="307" alt="j124 q4 nPolio 2000" src="https://user-images.githubusercontent.com/88923290/183426169-5dbdfcc1-c29f-40df-b61b-491df93a3860.png">

Polio year 2014

<img width="304" alt="j124 q4 nPolio 2014" src="https://user-images.githubusercontent.com/88923290/183426198-f8db2c25-40a1-48e9-a259-5cb6c802ea43.png">

There are 9 different counties in total from this data, no county shows up twice in the same vaccination chart.  

5. Which counties with the lowest vaccination rates have increases or decreases in their vacciantion rates from 2000 to 2014? 

For this pivot table, a filter to choose the 8 counties from question 4 will be needed(Tuolumne was excluded as it had no data for 2014). 

<img width="285" alt="j124 q5 filter" src="https://user-images.githubusercontent.com/88923290/183428693-3479272a-acdf-4ca8-9768-94ef1b866b3a.png">

>just like the year filter, clear all and search/select the counties needed

First pivot table will be for MMR

<img width="405" alt="j124 q5 nMMR" src="https://user-images.githubusercontent.com/88923290/183428910-85cb8fdf-b8da-44ca-a091-8e06bb3fdb6e.png">

Year 2000 to 2014- Humboldt decreased by 14.1%, Nevada decreased by 10.2%, Placer increased by 3.7%, San Benito increased by 19.1%, San Luis Obispo decreased by 11.5%, Santa Barbara increased by 9.7%, Santa Cruz decreased by 0.1%, Shasta decreased by 12.5%.

Almost all counties had a drastic change from 2000 to 2014. 

DTP, create a copy of the previous pivot table and repplace nMMR/NS with nDTP/NS. Do the same for Polio. 

<img width="408" alt="j124 q5 nDTP" src="https://user-images.githubusercontent.com/88923290/183430369-45ccab6c-fb4b-4ded-aaa1-ea18fe67f83b.png">

Year 2000 to 2014- Humboldt decreased by 12.2%, Nevada decreased by 6.9%, Placer increased by 4%, San Benito icnreased by 14.5%, San Luis Obispo decreased by 12%, Santa Barbara increased by 8.7%, Santa Cruz decreased by 4.1%, Shasta decreased by 12.6%.

Once again counties have shown drastic changes in vaccination rates. 

Polio

<img width="411" alt="j124 q5 nPolio" src="https://user-images.githubusercontent.com/88923290/183431295-c58f1325-eac0-419d-ae7a-70c3ed916a72.png">

Year 2000 to 2014- Humboldt decreased by 13.2%, Nevada decreased by 4.9%, Placer increased by 2.4%, San Benito increased by 14.5%, San Luis Obispo decreased by 12.9%, Santa Barbara increased by 10.2%, Santa Cruz decreased by 4.4%, Shasta decreased by 10.8%. 

Drastic changes in vaccination rates can be seen throughout each pivot table. Humboldt, Nevada, San Luis Obispo, Santa Cruz and Shasta all had a decrease in vaccination rates from 2000 to 2014. Placer, San Benito, and Santa Barbara had increases in vaccination rates from 2000 to 2014. 

# Data Visualizations

![yfAAf-polio-rates](https://user-images.githubusercontent.com/88923290/183448211-435a76b3-5afd-473f-9ed2-b531c2514d9e.png)

![yfAAf-dtp-rates](https://user-images.githubusercontent.com/88923290/183448715-f86ca556-dbd3-4b28-8e1c-853298f8d8c7.png)


![yfAAf-mmr-rates (1)](https://user-images.githubusercontent.com/88923290/183448881-d7d58578-7715-4ded-bd02-ada3457a34b3.png)
