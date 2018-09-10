
Protocols to Set Up for Head Position Classification
====================================================
The head position protocol includes 14 landmarks. These landmarks are used to calculate 17 measurements. These 17 measures are then used in two hybrid GUIDE forest prediction models to classify head position.


Landmarking Protocol
--------------------
Each landmark is placed in the anatomical midsagittal plan allowing for the measurements to be calculated in 3D.

.. figure:: docs/landmarkHP.PNG
    :scale: 75%
    :alt: This figure identifies all landmarks necessary to classify head position. All landmarks should be placed in the anatomical midsagittal plane rather than the scan midsagittal plane. 


Anterior Nasal Spine (ANS)
__________________________


Posterior Nasal Spine (PNS)
___________________________


Opisthion
_________


Spinous Process of C7 (SpPro7)
______________________________


Posterior Superior corner of C2 Apex (PSA)
__________________________________________


Anterior Tubercle of Atlas (AT1)
________________________________


Posterior Inferior Margin of vertebral body
___________________________________________


Posterior Superior Margin of C7 vertebral body
______________________________________________


Anterior Inferior Margin of C2 and C7 vertebral bodies
______________________________________________________



Measurements
------------

This protocol utilizes 17 measurements to quantify head position.  These measure assess both the face plane and the neck position inorder to predict if a image is in a flexed, neutral, or extended position. 



Head Measures or Face Plane Measures
____________________________________

ANS-PNS Plane
+++++++++++++

This measure calculates the angle of the nasal spine from a horizontal plane through the imaging scan.


Maxillo-Pharyngeal Angle
++++++++++++++++++++++++

This measure calculates the angle from the posterior nasal spine to the anterior tubercle of C1 to the anterior inferior point of C2.


Modified Bhalala head tilt angle
++++++++++++++++++++++++++++++++

In Bhalala et al., 2016 the head tilt angle used connected the occipito-ophisthion line and the ophisthion-C7 spinious process line, however due to the restricted field of view in many retrospective scans, which cut off the occiput landmark this protocol modified the angle to the posterior nasal spine.  The modified angle is comparable dur to structural connection of the cranium with limited change in the relationship of the occiput to the PNS.


Neck Measures
_____________


Antero-Posterior Ratio
++++++++++++++++++++++
The ratio of the anterior to the posterior length from the inferior borders of C2 to C7.


Antero-Porsterio Distance Difference
++++++++++++++++++++++++++++++++++++

The difference between the anterior and posterior lengths from the inferior borders of C2 to C7.


 


