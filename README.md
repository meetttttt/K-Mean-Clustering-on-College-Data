# K-Mean-Clustering-on-College-Data
Work Flow:
Collect Data ---> Preprocessing Data---> Exploring Data ---> Model Fitting ---> Evaluation

We will be using K-Means Clustering for Segregating University as Private University or Public University

What is K-Mean Clustering?
K-Means Clustering is an unsupervised learning algorithm that is used to solve the clustering problems in machine learning or data science.K-Means Clustering is an Unsupervised Learning algorithm, which groups the unlabeled dataset into different clusters. Here K defines the number of pre-defined clusters that need to be created in the process, as if K=2, there will be two clusters, and for K=3, there will be three clusters, and so on

The working of the K-Means algorithm is explained in the below steps:
- Select the number K to decide the number of clusters.
- Select random K points or centroids. (It can be other from the input dataset).
- Assign each data point to their closest centroid, which will form the predefined K clusters.
- Calculate the variance and place a new centroid of each cluster.
- Repeat the third steps, which means reassign each datapoint to the new closest centroid of each cluster.
- If any reassignment occurs, then go to step-4 else go to FINISH.
- The model is ready.

About Data:
- add Codeadd Markdown
- Apps: Number of applications received
- Accept: Number of applications accepted
- Enroll: Number of new students enrolled
- Top10perc: % of new students from top 10% of their high school class
- Top25perc: % of new students from top 25% of their high school class
- F.Undergrad: Number of full-time undergraduates
- P.Undergrad: Number of part-time undergraduates
- Outstate: Out-of-state tuition
- Room.Board: Room and board costs
- Books: Estimated book costs
- Personal: Estimated personal spending
- PhD: % of faculty with PhDs
- Terminal: % of faculty with a terminal degree (PhD/JD/MD/MBA/etc)
- S.F.Ratio: Student/faculty ratio
- perc.alumni: % alumni who donate
- Expend: Instructional expenditure per student
- Grad.Rate: Graduation rate

Conclusion:
- This Algorithm performed well,
- Where we were using 17 features(but we had 19 columns but one was label that is whether it is private or not and other was name of the University ) to create 2 cluster (Private and Goverment)
- Here we had had only two cluster and only 777 rows due to that our accuary of the model is less, however we can increase the accuracy by adding more data as well as adding new clusters to it.
- Here we had an advantage since we had labels however in real world dataset we may not get labels, here we had label so we have done evaluation of clustering.
- Thats it we are done with K-Means Algorithm.....!!!








