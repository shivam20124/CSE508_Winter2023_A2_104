# CSE508_Winter2023_A2_104
Repository for Assignment 2 of Information Retrieval

Q1:
For this question we used "_text_extraction.py" to extract text from the given dataset and updated the files in the folder "CSE508_Winter2023_Dataset".
After this we processed all the files and stored them in the folder "Processed_Files".
Next step was to create the TF-IDF matrix, which was done in the 'tf_idf.ipynb' file. TF-IDF matrix was created for all 5 weighting schemes and stored as CSVs for referring in the future.
Due to large sizes these files have been uploaded to Google Drive, link for each file corresponding to a weighting scheme is as follows:
1. Binary Scheme - https://drive.google.com/file/d/1EzbzH_FIZEm1vNeuUdykA5EG1_99tj2N/view?usp=sharing 
2. Raw Count Scheme - https://drive.google.com/file/d/1obnKhADxCj4CUhKZ7-a_OAzX4dBFPwby/view?usp=sharing 
3. Term Frequency Scheme - https://drive.google.com/file/d/1amMO4-1O0s0LTEhueJj83I68aVm18xaj/view?usp=sharing 
4. Log Normalisation Scheme - https://drive.google.com/file/d/13JTu1Z-tls98hZvGqs6N8jPsImNCpG3n/view?usp=sharing 
5. Double Normalisation Scheme - https://drive.google.com/file/d/1xVgiMTmCyVEGsMLFFKIfRB4L5P9RFsyD/view?usp=sharing 
The remaining functions of finding the top 5 relevant documents for each weighting score are also present in 'tf_idf.ipynb'
For Calculating Jaccard Coefficient, the code is present in the 'Jaccard.ipynb' file.


Q2:
1. Created the common tf-icf matrix in: 'preprocessing_tf_icf.ipynb' file. Gives the files: 'tf_matrix.csv' and 'tf_icf_matrix.csv'
2. Creating tf-icf features file for each doc in code file: 'features.ipynb'. Gives us the file: 'all_features.csv' ( the file is present her: https://drive.google.com/file/d/1hzf-rEdavU1d-AAfQPYmIERV7CtDNswN/view?usp=share_link  due to large size)
3. Implemented Naive Bayes in file: 'naive_bayes.ipynb'
4. For improving naive bayes, created a tf-idf matrix for the docs in: 'tf_idf_Q2.ipynb' file which stores the matrix in 'q2_tf_idf.csv'file.


Q3:
Initially we created the relevant csv from given dataset. For that the code is present in 'q3_file_creation.ipynb'. 
The CSV containing only relevant information is present in 'q3_data_csv.csv'
After that to find the DCG, nDCG and the Precision-ReCall Curve, the code is present in 'q3.ipynb'.