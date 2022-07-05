# CS521-GroupProject
Chest Xray diagnostic classification

This is a project that was done once in CS 542.

The data set consists of images of Chest Xrays of Covid/Normal and Covid/Normal/Bacterial Pneumonia/Viral Pneumonia images.  Labels were given.
During previous attempt, it was discovered that it was easy to distinguish between normal and covid but much more difficult to distinguish between Bacterial vs Viral pneumonia.  Many techniques were utilized that are optimization techniques in machine learning such as data augmentation, increasing numbers of epochs, reducing step size of gradient descent when closer toward goal.  However, these techniques lack scientific basis in its approach.  A more scientifically backed approach was discussed with professor Bargal of using scientific papers as backing.  So far what was found was that bacterial pneumonia tends to be localized in one lobe versus viral tend to exist in both.

This project will attempt to combine both the rigors of scientific research and innovations of deep learning/machine learning techniques to produce more robost algorithms for image classification to aid chest Xray diagnostics.  

If time permits, attempts will be made to utilize tehcniques taught in CS542 to trace explainability.

For full transparency, previous data and assignment notes were uploaded in the folder as well.  Previous attempt was made with teammate Maria Smith-Jones, a computer engineering masters student at BU.  Many useful techniques were used and accuracy was great.  However, the amount of resource required was significant and run-time was long.  Google Colab will be utilized for GPU computational power in this attempt.  
