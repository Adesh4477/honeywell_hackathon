                                                                                                                      #Honeywell Hackathon

Steps that i have taken to complete this hackathon :-

    1. After uploading the dataset to my notebook I found that each flight is having their unique id but completely shuffled in data.

    2. Then I sorted the dataset according to their unique id and timestamps so i can read the journey of each flight individually.

    3. I draw the line plot to visualize the anomaly which we receive in the dataset.

    4. I removed the NaN values to make it a fast prediction instead I would have also imputed the NaN value with their mean value of window size=5 to 10. 

    5. Altitude may give wrong sense to my original data after imputing so i didn’t include it and only used “latitude” and “longitude” for some flights.

    6. I have tried different combinations of field values to detect anomalies.
    
    7. Two models i used 
        A. IsolationForesrt which is an ensemble model combination of more model(decision tree , binary trees) The IsolationForest ‘isolates’ observations by randomly selecting a feature and then randomly selecting a split value between the maximum and minimum values of the selected feature.
        
        B.K- NearestNeighbour a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point.

    9.Then I compared these 2 models and then how closely they have detected anomalies.
    
    10. After detecting from the model I draw the line graph to visualize the anomalies.
