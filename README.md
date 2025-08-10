A Python-based exploratory analysis and clustering project using insurance customer data to uncover demographic trends, segment customers, and visualize health-related cost patterns.

Features involved-
Data Preprocessing: Checked for null values in the dataset, Scaled numerical features (age, bmi, children, charges), One-hot encoded categorical variables (sex, smoker, region), Created age categories- Young Adult, Senior Adult, Elder.

Exploratory Data Analysis (EDA): Age-Based Segmentation - pie chart of age category distribution, Average and median charges per age group. Weight Status vs. Charges - Classified individuals into BMI-based categories, Interactive scatter plot of age vs. charges for each category. Obese Smokers vs. Obese Non-Smokers - Scatter plot showing clear cost separation between obese smokers and obese non-smokers.

Clustering: K-Means Clustering- Applied Elbow Method (Yellowbrick) to find optimal clusters,  Visualized BMI vs. charges clusters with centroids. Hierarchical Clustering - Used Agglomerative clustering, Generated a dendrogram to display hierarchical structure.
