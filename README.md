# COM404E
breast cancer ml modell
COM 404E – Project on Breast Cancer using ML
Mo#va#on
Breast cancer is considered a multifactorial disease and the most common cancer in 
women worldwide with approximately 30% of all female cancers (i.e. 1.5 million 
women are diagnosed with breast cancer each year, and 500,000 women die from 
this disease in the world). While breast cancer remains a prevalent health concern, 
the field of medicine is experiencing an exciting revolution in its diagnosis and 
treatment. The journey of breast cancer begins with a rebellion within the body. Cells 
in the breast lose control of their growth, multiplying at an alarming rate. This 
uncontrolled proliferation often leads to the formation of a tumor, which can be visible 
on an X-ray or palpable as a lump. Early detection of these tumors holds immense 
significance, as it vastly increases the chances of survival.
However, the critical challenge lies in accurately classifying tumors as either 
malignant (cancerous) or benign (non-cancerous). This distinction is crucial, as 
malignant tumors have the ability to invade surrounding tissues and even spread to 
distant regions of the body, posing a significant threat to health. Benign tumors, on 
the other hand, remain localized and, while not cancerous, can still cause serious 
issues if they press on vital structures like blood vessels or nerves.
Background- The Biology
Breast cancer develops from breast cells and is considered a leading cause of death 
in women. This disease is classified into two subtypes: invasive ductal carcinoma 
(IDC) and ductal carcinoma in situ (DCIS). Over many years, it has been demonstrated
that breast cancer can be identified through several methods such as mammography, 
X-ray, ultrasound (US), Portion Emission Tomography (PET), Computed Tomography, 
temperature measurement and Magnetic Resonance Imaging (MRI). Usually, the 
golden standard approach for breast cancer diagnosis is a pathological process. In 
order to maximize visibility, the extracted tissue is stained in the lab before being 
subjected to imaging analysis. The staining procedure frequently employs 
Hematoxylin and Eosin (H&E). In most cases, Histopathological image analysis and 
genomics can both be utilized to identify breast cancer. A histopathological image is 
a microscopic picture of breast tissues and is very helpful in the early treatments of 
cancer. In order to predict and identify cancer early using ML, molecular analyses of 
tissues can be performed through a trained model based on digitized
histopathological images (data set).
Required- The Machine Learning
You will be required to apply four classification algorithms on the breast cancer data 
set namely K-Nearest Neighbor (K-NN), Support Vector Machine (SVM), Decision 
Tree (c4.5) and Random Forest. Ultimately, the goal state is to determine which 
among the four classification algorithms has the best performance. 
You will be required to mount your notebook on Github and enter the URL to your 
Github on the excel sheet to be provided in a separate communication. Remember 
to show all the outputs in your notebook foreach implementation. Equally, add 
relevant headings and comments to make it easy to follow your code. 
Dataset
Your are free to use any breast cancer dataset available on a pubic repositories like Kaggle, 
UCI, CDC, various clinics or government data sets. However, the recommended is the breast 
cancer Wisconsin data set. 
Please make sure to provide the URL poinEng to the source of the data set as a comment in 
your notebook just in case I need to understand your data set more.
Tasks
a) Load the data
b) Display the data frame information
c) Display the first and last tuples of the data set
d) Display the descriptive statistics 
e) Display the class label distribution
f) Use seaborn to display count plot for the class label
g) Use seaborn to display a joint plot with any two variables of your choice.
h) Determine based in the data set, whether you want to use category encoders
i) Split the data such that 25% is reserved testing
j) Show the shape of training set and the test set
k) Train a model using K-NN 
a. Show the confusion matrix
b. Show the heat map
c. Show the classification accuracy
d. Compare the training and testing accuracy
l) Train a model using SVM
a. Show the confusion matrix
b. Show the heat map
c. Show the classification accuracy
d. Compare the training and testing accuracy
m) Train a model using Decision Tree
a. Show the confusion matrix
b. Show the heat map
c. Show the classification accuracy
d. Compare the training and testing accuracy
n) Train a model using Random Forest
a. Show the confusion matrix
b. Show the heat map
c. Show the classification accuracy
d. Compare the training and testing accuracy
o) Demonstrate by way of a plot, which ml algorithm performs better from your
results above
