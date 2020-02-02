# Distance_from_coordinates

This assignment comprises of the various functions in the SciKit library to use to automate finding the distance 
from consencus block in California to various other places such as LA, Seattle, San Francisco. The method finds 
distance using Euclidean distance formula with the help of coordinates of the mentioned places obtained from Google.

The stepwise methodology of the entire assignment was :

1.The data used is California Housing data obtained from StatLib repository. Dataset contains 8 attributes/feature variables
  of which the last two are latitude and longitude, solidly indexed as 0=Latitude, 1=Longitude.

2.Creating a class which inherited from the BaseEstimator base class, specializing with TransformerMixin.

3.Creating a DropColumn class which helps in choosing only the last two required columns.

4.Since distance from various points/places can be requested, hence FeatureUnion was used, which parallely processes the input 
  coordinates of given places.

5.Entire methodology/workflow is encapsulated into a pipeline to maintain track.

6.R^2 score is also calculated.

Automation in steps starts from step 4.

LEARNINGS FROM THE ASSIGNMENT:

a) Implementation of CustomEstimators, and understanding how they are used.

b) Automating the entire process, instead of hard coding the desired.

c) How to actually implement FeatureUnions.
