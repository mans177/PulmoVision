# PulmoVision
My Graduation Project

Deep learning – Based Mobile Application for Classifying Diseases through Chest X-Ray Images

ABSTRACT:
In the field of medical diagnostics, the analysis and understanding of X-ray images, particularly 
those categorizing lung conditions such as COVID-19, pneumonia, and normal states, are a 
significant area of focus. This study set out to evaluate and compare the performance of three 
widely used deep learning CNN models — VGG16, InceptionV3, and ResNet50 — for the 
classification of these specific X-ray images. These models were trained and tested using a 
common dataset comprised of these three categories, with accuracy serving as the primary 
evaluation metric.

Our findings revealed distinct differences in the performance of the tested models. ResNet50 
emerged as the leading model due to its superior accuracy of 0.9643, a testament to its robust 
architecture and optimization. On the other hand, InceptionV3 and VGG16 models achieved 
accuracies of 0.9472 and 0.9596, respectively.

Following the model assessment, ResNet50 was incorporated into a mobile application through 
a Flask API connection, allowing for real-time X-ray analysis. This application, capable of 
providing probability prediction for a specific diagnosis, demonstrated high efficacy in its 
accurate predictions and high usability due to its user-friendly interface in preliminary tests. 
This application has the potential to enhance medical decision-making processes by offering a 
convenient platform for obtaining a secondary opinion.
