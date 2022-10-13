# machine_assignment
The given problem corresponds to a unsupervised machine learning algorithm since there are no specific labels to each data point , we have to understand the pattern underlying data and do our predictions.

In this problem I have used K means clustering for clustering the data into two categories i.e for phishing website category and for genuine website category.
Through the phishing website prediction I understood various characteristic of a phishing website which are:
A.Not using IP address
B.Long Url to hide phishing part
C.Using tiny url
D.Redirecting "//"
E.Adding prefix or suffix separated by(-)
F.Small domain registration length
G.Using non standard port

It can be clearly understood that the values corresponding to various parameters of phishing website would be lower compared to a genuine website, hence the cluster corresponding to phishing website would be labelled as zero and that of genuine website would be labelled as 1.
