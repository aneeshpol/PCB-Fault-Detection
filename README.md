# PCB Classification
This is a group project carried as a part of the course Conputer Vision. 

Printed circuit board(PCB) is the basic carrier in all electronic devices. The quality
of PCB directly impacts the performance of electronic devices. Automated detection of
defects of PCB is a problem which many researches are interested in for quite a long time.
Three datasets were given to us as a part of the assignment. The problem statement of the
assignment is to classify the PCB image as defective or non-defective . 

## Data Pre-processing 

As the data is highly imbalanced, we used oversampling techniques. Moreover, the test, train and validation sets are created such that there is no overlap between the sets. Data augmentation is used. The data is normalized. 

For detailed procedure, please check the report. 

## Experiments 

We used transfer learning in this project as the dataset is small. We tried various models. Inception gave us the best results. 

## Architecture
Inception architecture
## Results 

Please check the notebook PCB_classification.ipynb for the code. 

For test data, we got the following results.  

**Precision of finding defective data : 0.78788**   
**Precision of finding non-defective data : 0.99202**  
**Recall for finding defective data : 0.86667**  
**Recall for finding non-defective data : 0.98611**  
**Accuracy of finding defective data :  0.86666**  
**Accuracy of finding non-defective data : 0.98611**  
**F1 Score for defective data : 0.82540**  
**F1 Score for non-defective data : 0.98905**  


