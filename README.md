# Breast-Cancer-Detection

This project involves training two different machine learning models(Logistic Regression, Random Forest Classifier) in order to detect and classify breast cancer as benign(B) or maliant(M). The dataset used for this prediction consists of features computed from a digitized image of a fine needle aspirate (FNA) of the breast mass. These features describe various characteristics of the cell nuclei present in the image.For each cell nucleus, ten real-valued features are computed, which are:

1.  Radius: The mean distance from the center to points on the perimeter of the nucleus.
2.  Texture: The standard deviation of gray-scale values in the nucleus.
3.  Perimeter: The perimeter of the nucleus.
4.  Area: The area of the nucleus.
5.  Smoothness: A measure of local variation in radius lengths.
6.  Compactness: Computed as the square of the perimeter divided by the area minus 1.0.
7.  Concavity: Describes the severity of concave portions of the nucleus contour.
8.  Concave points: Represents the number of concave portions of the nucleus contour.
9.  Symmetry: Measures the symmetry of the nucleus.
10. Fractal dimension: This feature approximates the "coastline" of the nucleus, using the concept of fractal geometry.

At the bottom, I have tried to create a random search using RandomizedSearchCV with parameters but I get error for the .fit function which is 'penalty' parameter of LogisticRegression must be a str among {'elasticnet', 'none' (deprecated), 'l1', 'l2'} or None. Got 'None' instead. I tried with differently declared parameters, it didn't worked out so I finalized the project.
