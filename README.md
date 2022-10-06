# Identification-of-crime-prone-areas
The goal of analysis of crime prone areas is to identify and analyze patterns and trends in crime in specific regions. It is possible to identify regions with a high probability for crime occurrence and view crime-prone areas using our system. Computerized crime data analysis can aid law enforcement agencies in solving crimes quicker as a result of the increasing use of computers. We can discover previously unknown, useful information from an unstructured dataset using data mining techniques.
# K-Means
The system determines the low, medium and high areas of crime based on the dataset. 
K-means process consist of the following steps:
1. Choose k number of clusters as initial step.
2. Choose a set of K instances as centers of the clusters.
3. Each instance assigned by the algorithm to the cluster which is closest.
4. The cluster centroids are recalculated either after whole cycle of re-assignment or each instance assignment.
5. The process is iterated.
The algorithm requires specifying k number of clusters in advance. It is unable to handle noisy data and outliers and not suitable to discover clusters with non-convex shapes.
# DBSCAN
It requires epsilon (Eps) as one parameter value and minimum number points as the other parameter. (MinPts).It begins with a random point as its starting point. It then identifies and joins all the nearby points within distance Eps of that particular starting point. 
A cluster is formed when the number of nearby points joined is greater than or equal to MinPts. If the nearby points is less than the minimum number of points the particular starting point is declared as noise. The start point is then marked as visited. 
The algorithm repeats the evaluation process for all the neighbors’ repeatedly. If the number of neighboring nodes is less than MinPts, the point is marked as noise. 
#Group members:
1. Janhavi Jeevan Jaygade
2. Mukadam Suha Mohamed Husain
3. Rahul Kaushal Prasad
4. Upparakakula Kavyashree Ramesh
