# Gene expression analysis
This project describes the applications of  (1) classifier design, (2) error estimation
and (3) feature selection techniques to model a gene expression dataset . The data is provided in 
the Training_Data.txt and Testing_Data.txt files. 
This project analyzes gene expression in breast tumor biopsies from 295 patients. The dataset contains 70 genes
that predict the outcome of the disease after initial treatment. The outcome of the disease depends on the two classes- 'the good prognosis'
and 'bad prognosis'. The good prognosis group were disease free for atleat five years after the first treatment and
the bad prognonsis group developed distant secondary malignant growths within the first five years.
These genes were obtained through feature selection. 

The first column in the datasets contain the patient ID and the last column contain the label (1= good prognosis and 0=bad prognosis)
The first row contains the gene sysbol names. The testing data set is used for test-set error estimation. 

 Searched for classifiers and gene-feature sets that best discriminate the two prognosis classes on the training data, and use
 the testing data to determine their accuracy. The classifiers were designed based on four classification rules LDA, Linear SVM, Non-linear SVM with Gaussian kernel and neural network
with 5 neurons and one hidden layer.  
