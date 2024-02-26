# Master-Thesis
## Abstract

Food is fundamental for human beings, as it is indispensable for health and, above all,
for life itself. In recent years, the recording and sharing of recipes in online repositories
has led to a rapid growth of food computing: there is a large-scale availability of online
recipe collections that offer users the opportunity to access a wide variety of recipes.
However, this can be challenging and can make it difficult for users to discover recipes relevant to their request. 
In order to meet the customized needs of users, Recommendation Systems have been developed.
Compared to other Recommendation Systems applied to general domains such as films,
music or products, food recommendation is highly relevant to human health and, therefore, plays a critical role in human food choices. Food recommendation involves more
complex and multifaceted information: in addition to satisfying user preferences, it is
therefore equally important to include health scores, which is why Food Recommendation Systems have recently received increasing attention due to their importance for a
healthy lifestyle.
Added to this is the introduction of knowledge graphs (KG) into Recommendation Systems in recent years as collateral information. It has attracted significant interest as it
can enable a Food Recommendation System to understand latent reciprocal relationships
better and make recommendation results more explainable.
Nevertheless, its use in food recommendation has not been extensively studied, and to
fill this gap, this thesis work aims to describe the implementation of a Food Recommendation System based on a knowledge graph that can provide users with recommendations that meet their own customized requirements, while considering the healthiness of recipes and the user’s unique health conditions, such as food allergies or specific food diets.
To achieve this, a Food Knowledge Graph is reconstructed and, starting from its initial structure, a mechanism is defined for inserting new characteristics aimed at further extending the created FoodKG with new labels that consider, in the ingredients that make up a recipe, their healthiness, the possible presence of allergens or their unsuitability for particular food diets.
From this, it is possible to implement a content-based Recommendation System whereby
the recommendation problem is seen as a binary classification problem in which the intention is to predict which recipes the user might or might not like. In this case, in order
to cope with the scarcity of user interaction with the recipes, semi-supervised learning,
and self-training techniques are applied, which resulted in the recommendation of the six
recipes most suitable for the user. 
Finally, a Web App is developed and implemented through which users can interact with
the recipe Recommendation System created.
