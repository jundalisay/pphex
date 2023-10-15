# Pantry Circle for the ADB "Visualizing Climate Change & Resilience Challenge"

[Pantry Circle](https://pantrypoints.com/circle) is our proposed system that implements a circular economy by **embracing** global warming, with its disasters.

Its first implementation is called **Village Contract Farming** (VCF). In the Philippines, we will implement this VCF as "Basurayuda", which is a program that mobilizes unemployed people to collect plastic waste and kitchen waste to be recycled and turned into compost.

This system relies on **communities and moneyless systems** in order to create a "common economy" powered by "common interest". This will reduce exposure to market forces which are powered by money and "selfish interest", and the subsequent stagflations and financial crises that are inseparable from modern markets. 

This reduces the impact of fuel and energy shortages by **sourcing nutritious food from nearby areas** in order to **systemically reduce the carbon footprint of agriculture**. Only grain, meats, and fish will be sourced from distant areas. Governments will then only need to reduce the impact of grain supply.

In the Philippines, vegetables are sourced from Baguio which is over 200 kilometers away. As transportation is the 2nd largest energy user, village contract farming can save energy and reduce greenhouse gases by sourcing those same vegetables between 0.2-2 kilometers instead of 200 kilometers.

Essential to this system is the proper prediction of rainfall and temperature, as well as human behavior, in order make community food systems as secure as possible.

This will create resilient communities which will then be the backbone of the new globally-warmed economy.  


## Secret Sauce: Fellow-Feeling from Moneyless Systems

The current market model relies on money. Our system uses both money *and* barter. 

This combines the selfish-interest of money and the common interest of barter. Our barter uses points as a store of value and is not the immediate barter that we often think of. 

An agricultural laborer can till the soil in exchange for a future revenue of crops from that very soil.

In effect, this 'funds' the system directly with food which is essential to activity which forms the base of any economy of any country.

There are 3 major steps to build this:

1. Impact and Nutrition
2. Agriculture
3. Climate



## Step 1a: Know the Impact of the Different Crops

This is our first filter. We have to base our system on food that will not make the global warming problem worse than it already is. 

We see that Coffee, Chocolates, Sugared Food Items, Meat, and Seafood have high environmental impact. 

Vegetables, grains, and certain fruits have the least impact.   


## Step 1b: Know the Nutrition Content of Native Vegetables and Fruits 

We focus on such vegetables, grains, and fruits as candidates to be our crops. 

#### Data Source: https://www.lose-weight-with-us.com/

Taken From: https://www.kaggle.com/datasets/yoyoyloloy/fruits-and-vegetables-nutritional-values?resource=download

Fruits: https://www.lose-weight-with-us.com/fruit-nutrition-facts.html
Vegetables: https://www.lose-weight-with-us.com/vegetable-nutrition-facts.html


<!-- - Fruits: https://www.fda.gov/Food/IngredientsPackagingLabeling/LabelingNutrition/ucm063482.htm
- Vegetables: https://www.fda.gov/Food/IngredientsPackagingLabeling/LabelingNutrition/ucm114222.htm
- Seafood: https://www.fda.gov/Food/IngredientsPackagingLabeling/LabelingNutrition/ucm114223.htm

Taken from: https://www.kaggle.com/datasets/lazycoder00/-nutritionalfacts-fruit-vegetables-seafood -->



We see that the following offer good nutrition:

High Nutrition Fruits:
- Jackfruit
- Passionfruit
- Banana
- Pomegranate
- Guava
- Calamansi


High Nutrition Vegetables per weight:                                                                               
- Chickpeas
- Soybeans
- Beans
- Lentils
- Peas
- Sweet corn
- Potatoes
- Tomatoes
- Kale
- Ginger


We avoid the low nutrition ones.

Low Nutrition Fruits:
- Watermelon
- Melon
- Starfruit
- Peaches
- Grapefruit
- Papaya


Low Nutrition Vegetables:
- Squash 
- Lettuce
- Cucumber
- Celery
- Peppers
- Eggplant

Most Low Nutrition crops aid digestion but have less energy and substance.


But not all crops are equal. Some require a lot of water, some need sun, some need calcium. These requirements must match the constraints of land. 


## Step 2: Know which of those nutritious crops are most resilient to heat (high temperature and less rainwater)

We find the following:
- Beans
- Sunflowers
- Okra
- Soybean
- Peanuts
- Potatoes


- Corn 
- Tomatoes



Plot.plot({
  marks: [
    Plot.dot(vegs, {x: "energy (kcal/kJ)", y: "water (g)"}),
    Plot.text(vegs, {text: "name", x: "energy (kcal/kJ)", y: "water (g)", dy: -8})
  ]
})

https://www.kaggle.com/datasets/prateekkkumar/crop-water-requirement
Plot.plot({
  marks: [
    Plot.dot(fruits, {x: "energy (kcal/kJ)", y: "water (g)"}),
    Plot.text(fruits, {text: "name", x: "energy (kcal/kJ)", y: "water (g)", dy: -8})
  ]
})


## Step 3: Find Rainfall and Temperature Trends per City




### Data Sources:

https://observablehq.com/d/a390276fe66f0a81

https://www.pagasa.dost.gov.ph/climate/climate-monitoring

https://www.kaggle.com/datasets/yoyoyloloy/fruits-and-vegetables-nutritional-values?resource=download



<!-- https://www.fda.gov/Food/IngredientsPackagingLabeling/LabelingNutrition/ucm063367.htm -->


