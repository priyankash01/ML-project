# iNeuron_Mushroom_Classification

<b>ABSTRACT :</b>
Mushrooms have been consumed since earliest history. The word Mushroom is derived from the French word for Fungi and Mold. Now-a-days, Mushroom are popular valuable food because they are low in calories, carbohydrate, Fat, sodium and also cholesterol free. Besides this, Mushroom provides important nutrients, including selenium, potassium, riboflavin, niacin, Vitamin D, proteins and fiber. All together with a long history as food source. Mushroom are important for their healing capacity and properties in traditional medicine. It has reported beneficial effects for health and treatment of some disease. Many nutraceutical properties are described in Mushroom like cancer and antitumor attributes. Mushroom act as antibacterial, immune system enhancer and cholesterol lowering Agent. Additionally, they are important source of bio-active compounds. This work is a machine learning model that classifies mushrooms into 2 classes: Poisonous and Edible depending on the features of the mushroom. During this machine learning implementation, we are going to see which features are important to predict whether a mushroom is poisonous or edible.

<b>Problem Statement :</b>
The Audubon Society Field Guide to North American Mushrooms contains descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom (1981). Each species is labelled as either definitely edible, definitely poisonous, or maybe edible but not recommended. This last category was merged with the toxic category. The Guide asserts unequivocally that there is no simple rule for judging a mushroom's edibility, such as "leaflets three, leave it be" for Poisonous Oak and Ivy.

The main goal is to predict which mushroom is poisonous & which is edible.
This project aims at developing a machine-learning algorithm that will determine if a certain mushroom is edible or poisonous by its specifications like cap shape, cap color, gill color, etc. using different classifiers.

To do so, I have used the following classification methods:

1. Decision Tree Classifier
2. Logistic Regression Classifier
3. k-Nearest Neighbor Classifier
6. Random Forest Classifier

<b>DATASET : FROM THE KAGGLE WEBSITE Kaggle Link : https://www.kaggle.com/uciml/mushroom-classification</b>
<b>Architecture :</b>

![image](/Users/priyanka/Desktop/ARCHI.png)

<b>Web Interface :</b>

![image](/Users/priyanka/Desktop/Screenshot 2024-05-16 at 7.29.51 PM.png)

<b>Summary :</b>

 - The target column has 2 class type one is 'poisonous' which has 3916 counts and second is 'edible' which has 4208 counts so we have nearly equal counts for poisonous and edible classes in our data. Hence we can say that our data is balanced.
 - There are 4 types of cap-surface in a mushroom and also it suggests that 'edible' mushrooms do not have 'cap-surface' : 'g : grooves' according to our data.
 - The mushroom may or may not have bruises but still it could be poisonous or edible according to our data.
- The mushroom can have Gill Spacing as Close or Crowded but still it could be poisonous or edible according to our data.
- The mushroom can have Gill Size as Narrow or Broad but still it could be poisonous or edible according to our data.
- The 'edible' mushroom do not have Gill Color : Buff, Green and 'poisonous' mushroom do not have Gill Color : Red, Orange according to our data.
- The 'poisonous' mushroom do not have Stalk Root as Rooted type according to our data.
- The mushroom can have Stalk-Surface-Above-Ring as Smooth, Fibrous, Silky or Scaly but still it could be poisonous or edible according to our data.
- The mushroom can have Stalk-Surface-Below-Ring as Smooth, Fibrous, Silky or Scaly but still it could be poisonous or edible according to our data.
- The 'edible' mushroom do not have Ring-Type as Large and None and 'poisonous' mushroom do not have Ring-Type as Flaring according to our data.
- The 'edible' mushrooms do not have Spore-Print-Color as Green and 'poisonous' mushrooms do not have Spore-Print-Color as Purple, Orange, Yellow, Buff according to our data.
- The 'poisonous' mushrooms do not have Population Type as Numerous and Abundant according to our data.
- The 'poisonous' mushrooms do not have Habitat Type as Waste according to our data.
