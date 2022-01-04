# Uma-Vaidya-Project-on-Indian-Food

PROJECT NAME -: INDIAN FOOD ANALYSIS AND STRATEGIES TO INCREASE SELL

Table of Content-:


Reason to Choose these Project

Pandas Methods which are used in these project

Graph which are used

Workdone

Conclusion

Result


1)Reason to Choose these Project-:

I always feel that Indian cuisine is consist of a variety of regional and traditional cuisines native to the Indian subcontinent. Given the diversity in soil, climate, culture, ethnic groups, and occupations, these cuisines vary substantially and use locally available spices, herbs, vegetables, and fruits.Also being hardcore foody person I was curious 
to know trends and patterns of food consumption regionwise and statewise.So to analyse these all I have selected this project.Also I feel these types of analysis can help Restaurants,Food production companies and Distribution Chains to make some constructive decisions about their productions and sales.

3)Pandas Methods which are used in these project-:

info(),desribe(),values>0
isna().sum(),
dropna(),value_counts(),value.unique(),
idxmax(),idxmin(),nlargest()

4)Graph which are used-: ->For plotting i have used matplotlib.pyplot and seaborn

Bar graph
Pie chart
Countplot
Heat map
5)Workdone-:

By using value>0 i have deleted all the Negaitive values in the dataset which were not useful for analysis.

By using isna() i have checked if there are any blank values present in the dataset which were not useful for analysis.

By using dropna()i have deleted row containning blank values in the dataset which was not useful for analysis.

By using value_counts i have checked total how may types of Diets are there in dataset.Also I have displayed the same in bar graph format.

By using value.unique(),i have checked total how many types of courses are there is dataset.Because of this function repetative content was avoided.Also I have displayed the same in bar graph format.

By using idxmax and idxmin i have checked most liked and least liked flavor by food consumers.So accordingly that partcular flavored food production can be increased and logistics required for least liked flavor distribution can be diverted to more productive channel which will result in increased sale 

I used nlargest because by dataset is very big to visualize the data properly on the following graph i have drawn observations for the top (10) states and flavors.

I used masking technique alongwith idxmax(),idxmin() to know the information about max and min cooking and preparation time.I have shown the same using grid graph

I used groupby where i wanted to club 2 or more columns where reuired information was dependent on each other.

I used countplot where the data is more and to visualize it properly.

I have used corr() and sns.heatmap() to observe correlation between 2 different columns



6)Conclusion-:

From above analysis i have concluded that in given dataset,information is collected about food habits of people 
from different States

There are more number of vegetarians as compare to Non-vegetarians.

There are 4 categories named dessert,main course(most popular),snack and starter(Least liked)

There are 4 type of falours named spicy(most liked flavour),sweet,bitter and sour(Least liked flavour).

Maximum info is collected from West region i.e(34.38%)vs least from central(1.34%).

7)RESULT-:

I feel food companies should focus more on spicy & sweet food's production & distribuition in west region like Maharashtra 
where % of consumption is 19.44% and 16% respectively.

In North region like Punjab spicy food % is 16.67 where maximum attention should be given by food chains.

Also my observation is in Punjab Main course % is 18.92 and in Maharashtra it is 12.16% so in these areas more food items which are filling and those
which can substitute main course like "tawa fry "ready chapaties or ready to cook (in 5 mins)veg packets can be a very good option

Also there is list of items mentioned in my analysis where preparation time is less but cooking time is more for e.g laddu,aloo 
matar etc.Food companies can sell ready shallow fried laddu material,and half cooked vegies,which will save time of working women. 

Also there are some food items like Pani puri for which Preparation time is more as against cooking time.In such cases ready dry chatnis can be sold to save preparation time.

SO in nutshell,Food companies should focus more on region wise demand,statewise consumption and most liked flavored food items.Also they can creatively design ready to cook food packets which will save preparation and cooking time.Also logistics and distribution channels can shift their focus demandwise.  
