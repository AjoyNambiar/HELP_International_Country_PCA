# HELP_International_Country_PCA
# Business Objective
HELP International is an international humanitarian NGO that is committed to fighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities. Using country socio-economic data we need to identify countries which are in the direst need of aid. 

# Methodology: 
A nine feature socio-ecomic factor are provided for each of the 167 countries. These features are collinear
Clean the data and perform EDA. We will use derived metrics where suitable eg % Health converted to Heath per person
Data is standardized as features are different units and scale
Using Principal Component Analysis (PCA) we will attempt to reduce the dimension while retaining the information/ variance
From PC converted data we will attempt to cluster using unsupervised learning techniques like Kmeans and Hierarchical clustering cluster countries based on their socio-economic factors
We will treat the outliers i.e. countries with very high or very low development characteristics to enable clustering algorithm to work
Once under-developed country cluster is identified we will use is centroid/ mean/ characteristics to find the most under developing countries which require aid the most
A comparison of Kmeans and hierarchical clustering will be done and if variations seen will try to explain them
