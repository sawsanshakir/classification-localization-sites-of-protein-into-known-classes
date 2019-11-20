# classification-localization-sites-of-protein-into-known-classes

In this report we implemented random forest classifier to investigate the performance of predict the
Localization site of protein. Random forest is an ensemble-based schemes which make it suitable
for learning from imbalanced data.
We used three approaches to deal with imbalanced data. The first one, implement the random
forest algorithm and predict the 30% of dataset. The second trial was using class weights or cost
sensitive learning. That what make random forest more suitable for this problem. 
The last experiment was resampling the training dataset with oversampling algorithm SMOTE and
then training the random forest algorithm from balanced data. Generally, the best result we got with 
the random forest and Class weighted random forest has shown an improvement better than the oversampling algorithm.
