# CS521-Final Project
Chest Xray diagnostic classification

TO reproduce results:

download folder all, final-project-dede-sunshine-vgg16 and mobilenet

change: 

for vgg16

DATA_LIST: working directory for train - separated lobes data -2 class normal and abnormal

DATASET_PATH working directory for train - separated lobes data - 2 class normal abnormal

TEST_DIR  working directory for test - separated lobes data

TEST_DIR1 test data pneumonia bacterial - separated lobes

TEST_DIR2 test data pneumonia viral - separated lobes



for MobileNET

DATA_LIST working directory for train all 4 classes non-separated lobes

DATASET_PATH working directory for training data all 4 classes non-separated lobrs

TEST_DIR test data for all 4 classes non-separated lobes

*****DO NOT RUN data processing step **** this is left to show work but does not need to be run again

Then run each cell sequentially 




INTRO PRIOR TO WORK:
The data set consists of images of Chest Xrays of Covid/Normal and Covid/Normal/Bacterial Pneumonia/Viral Pneumonia images.  Labels were given.
During previous attempt, it was discovered that it was easy to distinguish between normal and covid but much more difficult to distinguish between Bacterial vs Viral pneumonia.  Many techniques were utilized that are optimization techniques in machine learning such as data augmentation, increasing numbers of epochs, reducing step size of gradient descent when closer toward goal.  However, these techniques lack scientific basis in its approach.  A more scientifically backed approach was discussed with professor Bargal of using scientific papers as backing.  So far what was found was that bacterial pneumonia tends to be localized in one lobe versus viral tend to exist in both.

This project will attempt to combine both the rigors of scientific research and innovations of deep learning/machine learning techniques to produce more robost algorithms for image classification to aid chest Xray diagnostics.  

If time permits, attempts will be made to utilize tehcniques taught in CS542 to trace explainability.

For full transparency, previous data and assignment notes were uploaded in the folder as well.  Previous attempt was made with teammate Maria Smith-Jones, a computer engineering masters student at BU.  Many useful techniques were used and accuracy was great.  However, the amount of resource required was significant and run-time was long.  Google Colab will be utilized for GPU computational power in this attempt.  

Links of found work:
https://ai.googleblog.com/2021/09/detecting-abnormal-chest-x-rays-using.html 
https://pubmed.ncbi.nlm.nih.gov/32575475/
