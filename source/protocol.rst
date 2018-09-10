
Head Position Protocol
======================
The head position protocol includes two two-step algorithms.

`pdf <docs/HP-Landmarks.pdf>` 


Training Cases
--------------

The GUIDE random forest algorithms require training cases to make predictions.  The training cases have been provided for each step of both algorithms. The training cases consist of six participants (3 male, 3 female) who were positioned into extreme extention, extreme flexion,  neutral with a closed mouth, neutral with an open mouth, and neutral with a mouthpiece to standardize the mouth position.


Measurements
============

This protocol utilizes 17 measurements to quantify head position.  These measure assess both the face plane and the neck position inorder to predict if a image is in a flexed, neutral, or extended position. 



Head Measures or Face Plane Measures
------------------------------------

ANS-PNS Plane
_____________

This measure calculates the angle of the nasal spine from a horizontal plane through the imaging scan.


Maxillo-Pharyngeal Angle
________________________

This measure calculates the angle from the posterior nasal spine to the anterior tubercle of C1 to the anterior inferior point of C2.


Modified Bhalala head tilt angle
________________________________

In Bhalala et al., 2016 the head tilt angle used connected the occipito-ophisthion line and the ophisthion-C7 spinious process line, however due to the restricted field of view in many retrospective scans, which cut off the occiput landmark this protocol modified the angle to the posterior nasal spine.  The modified angle is comparable dur to structural connection of the cranium with limited change in the relationship of the occiput to the PNS.


Neck Measures
-------------


Antero-Posterior Ratio
______________________

The ratio of the anterior to the posterior length from the inferior borders of C2 to C7.


Antero-Porsterio Distance Difference
____________________________________

The difference between the anterior and posterior lengths from the inferior borders of C2 to C7.




Set Up
======

To run this protocol you will need to download the GUIDE multi-purpose machine learning algorithm from `Dr Loh's website <http://www.stat.wisc.edu/~loh/guide.html>`_. Additionally each step of the following protocol will have a unique cost matrix, description text, input file, and .csv file with the training data.  


