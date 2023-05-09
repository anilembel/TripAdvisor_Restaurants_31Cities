<h1 align="center">
  <br>
  <img src="https://github.com/anilembel/TripAdvisor_Restaurants_31Cities/blob/main/Assests/BeCode_color_1.png" alt="Logo""></a></p>
<h3 align="center">Trip Advisor Europe Restaurants Analyses <a href="https://github.com/becodeorg"><strong>BeCode</strong></a></h3>
  <br>
  By Anıl EMBEL
  <br>
</h1>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h3 align="center"> Description  </h3>  


# Restaurant Dashboard
- Type of Challenge: `Learning`
- Duration: `8 days`
- Development Deadline: `03/05/2023 4:30 PM`
- Repo Deadline: `12/05/2023 4:00 PM`
- Challenge: Individual (or Team)

![restaurant_food](https://media.giphy.com/media/7JzHsh3UTip20/giphy.gif)


## Mission objectives

- Be able to use data visualization libraries `matplotlib`, `seaborn`, or data tools like PowerBI to explore the data.
- Be able to clean a dataset for analysis.
- Be able to use colors in visualizations correctly.
- Be able to establish conclusions about a dataset.
- Be able to find and answer creative questions about data.
- Be able to think outside the box.
- Be able to create a dashboard containg visualizations that bring business insights to the client.


## The Mission

I'm a data analysis consultant at an European travel agency. my mission is to help the company find business insights from their data that will help them grow their business. 

To do so, I will create a dashboard! What is important to include in the dashboard? Ideally, this dashboard would help travel agents make recommendation to travellers on the best food destination for their trips across Europe.

As a starting point, they provide you with data they scrapped from Trip Advisor, a popular travel website. 

Dataset: [TripAdvisor Restaurants Info for 31 Euro-Cities](https://www.kaggle.com/datasets/damienbeneschi/krakow-ta-restaurans-data-raw)


   
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h3 align="center"> EDA   </h3>  


<p>

Firstly, I dropped some columns which I was not planing to use (URL_TA, ID_TA, Ranking, Reviews). # Then I renamed some of the columns make it clear 

("Cuisine Style" : "Cuisine"),  ("Price Range": "PriceRange"),  ("Number of Reviews" : "Num_Reviews")
 
The raw data were generally regular but contained many null values. So I filled null values according to related values with  group by methods and their mode and medians. 

To make it work for my visualization, I took the unique cities and created them from a directive named countries. Also I changed the null values in the cuisine columns with Unknown because for the visualization it could be important

Also , I created a dictionary to hold the all cuisine types. I used it to fill some of the missing cuisine values, from the restaurant name. If the restaurant has its cuisine type inside of its name, fill the missing value with it.

I Replaced price range with a string values.
{"$": 'Cheap', "$$ - $$$": 'Avarage', "$$$$": 'Expensive'}
                                            
 In the last part I created a new CSV files for my visualizations on Tableau.                                            
                                            
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h3 align="center"> Visualizations  </h3>  

Link Of the Dashboard : https://public.tableau.com/shared/99FDH7FT6?:display_count=n&:origin=viz_share_link
<p>
    By using Tableau public in my visualizations, I prepared an analysis consisting of many sheets, 4 dashboards and 1 story + a visualization that gives the best advice in 3 different classifications for each city. Thanks to the dynamism of the dashboards, you can find answers to many questions.
                  
                  For example :

- What are the percentiles of cheap places in Brussels in general cuisine types?
- If I want to go to an expensive restaurant in Vienna, which is the best?
-You can find answers to many questions such as the most popular kitchen types in Europe, the city with the most points, etc.
</p>



 

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h3 align="center"> Installation </h3>
Clone the project

```bash
  git clone https://github.com/anilembel/TripAdvisor_Restaurants_31Cities.git
```
 Install the required packages using

```bash
  pip install -r requirements.txt
```
 
Go to the project directory

```bash
  cd YourPath/NLP_Movie_Recommendation
```

## Contact

<li> via Github : [Anil Furkan EMBEL](https://github.com/anilembel) </li>
<li> via Linkedin : [Anil Furkan EMBEL](https://www.linkedin.com/in/anilfurkanembel/) </li> 

