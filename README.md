# Task6 K-Nearest Neighbors (KNN) Classification                                                                                                                         

***TITLE**: K-Nearest Neighbors (KNN) Classifier with Decision Boundary Visualization*                                                                                   

**Description:**                                                                                                                                                            

This Python implementation demonstrates how K-values affect classification performance through dynamic decision boundary visualization. Key features include dual dataset support (built-in Iris dataset or custom CSV files), accuracy-K curve analysis, and confusion matrix reporting. The project visually reveals the bias-variance tradeoff in KNN algorithms.                                                                                                                                                

**Installation:**                                                                                                                                                        

1. Clone repository: git clone https://github.com/Sriyoshija/knn-classifier.git                                                                                             
cd knn-classifier                                                                                                                                                         

2. Install dependencies: pip install -r requirements.txt                                                                                                                                                                       

**Usage Instructions:**                                                                                                                                              

1. Configure knn_classifier.py:                                                                                                                                      

-> Set USE_BUILTIN_DATA = True for Iris dataset or False for custom CSV                                                                                                      
-> Specify CSV_FILE_PATH and TARGET_COLUMN for custom datasets                                                                                                            

2. Execute script:                                                                                                                                                   

python knn_classifier.py                                                                                                                                             

3. Generated outputs:                                                                                                                                                  

-> knn_accuracy_plot.png (Accuracy vs K-values)                                                                                                                          
-> knn_decision_boundaries.png (Visual comparison for K=1,5,15,30)                                                                                                         
-> Console logs with accuracy scores and confusion matrices                                                                                                             

**Dataset Requirements:**                                                                                                                                                 

Custom datasets must be CSV formatted with:                                                                                                                                 

-> First two columns as numerical features                                                                                                                              
-> Last column as class labels                                                                                                                                                  
-> Header row specifying column names                                                                                                                                     

**Key Findings (Iris Dataset):**                                                                                                                                        

1. Optimal K-value: 5                                                                                                                                                     
2. Test accuracy: 84%                                                                                                                                                     
3. K=1 shows overfitting (96% train accuracy)                                                                                                                           
4. K≥15 shows increasing underfitting                                                                                                                                     
5. Decision boundaries optimally balance complexity at K=5                                                                                                               

**Customization Options:**                                                                                                                                                

-> Adjust K_VALUES_TO_TEST in config for different K-ranges                                                                                                             
-> Modify PLOT_COLORS for visual customization                                                                                                                          
-> Change TEST_SIZE for train-test split ratio                                                                                                                              

**Contribution Guidelines:**                                                                                                                                          

1. Fork repository                                                                                                                                                     
2. Create feature branch: git checkout -b new-feature                                                                                                                  
3. Commit changes: git commit -am 'Add feature'                                                                                                                                       
4. Push branch: git push origin new-feature                                                                                                                                     
5. Submit pull request with detailed description                                                                                                                         












