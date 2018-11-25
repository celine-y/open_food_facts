# Title

Global food analysis

# Abstract

According to the Food allergy Research & Education, there have been over 170 reports of different foods causing allergies. In America, there is approximately 15 million people who have food allergies, and this number is rising. Between 1997 to 2011, the number of food allergies in children increased by 50%. More specifically, from 1997 to 2008, the presence of peanut/tree nut allergies have tripled in the United States. With this increase in allergies, we wanted to analyze how different countries in the world support the people with different kinds of intolerances to food (i.e. allergies) as well as those who require a specific diet (i.e. diabetes, high cholesterol, vegan, halal). From our analysis, we want to show how easy/hard it would be to support the different diets around the world. This way, when people are travelling, they can be prepared for the limited number of foods they can eat. For this project, we will be using the Open Food Facts Database.

# Research questions

+ How closely correlated (similar) are neighbouring countries' food?

+ Is the support for a dietary restriction similar in neighbouring countries?

+ How can we display the support for different types of dietary restriction on a map?

+ Also, what if we want to see the support for two or more dietary restrictions?

# Dataset

We’re going to use the Open Food Facts data set (https://world.openfoodfacts.org/data) It is an open source database, which provides nutrition facts for food products sold in each country, and all nutrition information was available in English. This can be very helpful to foreigners to understand food in this country. Currently, this database contains more than 90,000 records, all of the contents are contributed by volunteers, and its entire database can be downloaded for free.

The dataset has four main fields related to general information such as the barcode of the product, the contributor who first added the product, the url of the product and of course the name of the product. Other field is called tags, here we found information related to the packaging or  brands of the products. One of the main fields we’re going to analyze is the ingredients one. Another interesting field is nutrition facts correspond to the amount of a nutriment (in g, or kJ for energy) for 100g or 100 ml of product. Finally, in the misc. Data field  we have extra information such as image of the product, number of food additives or ingredients from palm  oil, carbon footprint (indicated on some products) and nutrition score defined by the UK Food Standards Administration (FSA).

For more information: [data-fields of Open Food Facts](https://static.openfoodfacts.org/data/data-fields.txt)

# A list of internal milestones up until project milestone 2

+ Setup: Done by November 8

  + Understand how the data is stored on the ADA cluster.

  + Look at the data and brainstorm ways to clean/process the data.

  + Brainstorm how to display the data.

+ Clean & Start Processing: Done by November 15

  + Clean the data from Open Food Facts

  + Start finding relationships between the different types of food in each country perhaps present them in a map.

+ Finish Processing & Analyzing: Done by November 22

  + Finish all graphs/maps needed

  + Write the conclusions from the graphs

+ Clean up: Done by November 25

  + Clean code, write comments as needed


# Questions for TAa

+ Is using just the Open Food Facts dataset enough to justify that a (i.e. vegan) person would be able to survive in certain countries? Or would it make more sense if we included the Cooking Recipe's dataset so that we can see the proportion of meals that person can make in the different countries?

+ Do we need to create our own database that join each food allergie with the allergen that provokes it?

# A list of internal milestones up until project milestone 3

+ Setup: Done by Dec 6

  + Create the map visualizations that depict the number/percentage of food available for each type of dietary restriction

  + Analyze the correlation of foods available between neighbouring countries.

+ Writing the Report: Done by Dec 13

  + Determine which type of report we want to do (i.e. Data story or traditional report)

  + Explain the algorithms we used when cleaning our data and displaying our graphs

  + Explain our results of what our results (data) shows and what it means
