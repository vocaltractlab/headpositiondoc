
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

This landmark is placed at the most anterior point of the nasal spine.

.. figure:: docs/ANS.PNG
     :scale: 75%
     :alt: This figure provides visual example of the placement of the ANS landmark.


Posterior Nasal Spine (PNS)
___________________________

This landmark is placed at the most posterior point of the nasal spine.

.. figure:: docs/PNS.PNG
     :scale: 75%
     :alt: This figure provides visual example of the placement of the PNS landmark.


Opisthion
_________

This landmark is placed at the most anterior-interior point on the posterior margin of the foramen magnum.

.. figure:: docs/OPI.PNG
     :scale: 75%
     :alt: This figure provides visual example of the placement of the OPI landmark.


Spinous Process of C7 (SpPro7)
______________________________

This landmark is placed at the most posterior point on the spinous process of C7. In the case of bifid spinous processes, the landmark should be placed on the midpoint of where the two sides deviate, instead of the exact most posterior point.

.. figure:: docs/SpPro7.PNG
      :scale: 75%
      :alt: This figure provides visual example of the placement of the SpPro7 landmark.


Posterior Superior corner of C2 Apex (PSA)
__________________________________________

This landmark is placed at the most posterior and superior corner of the apex at the anatomical midline of the odontoid. This landmark should be placed at the superior corner of the posterior border of C2.

.. figure:: docs/PSA.PNG
      :scale: 75%
      :alt: This figure provides visual example of the placement of the PSA landmark.


Anterior Tubercle of Atlas (AT1)
________________________________

This landmark is placed at the most medio-anterior point of C1 denoting the anterior tubercle of the atlas, C1.

.. figure:: docs/AT1.PNG
      :scale: 75%
      :alt: This figure provides visual example of the placement of the AT1 landmark.


Posterior Inferior Margin of vertebral body
___________________________________________

For C2 and C4 to C7, place the landmarks on each vertebrae at the most posterior and inferior point of the vertebral body in the anatomical midsagittal plane of the respective vertebral body.

.. figure:: docs/PI.PNG
       :scale: 75%
       :alt: This figure provides visual example of the placement of the PI landmarks.


Posterior Superior Margin of C7 vertebral body
______________________________________________

This landmark is placed at the most posterior and superior point on C7 vertebral body in the anatomical midsagittal plane of the vertebral body.

.. figure:: docs/PS.PNG
       :scale: 75%
       :alt: This figure provides visual example of the placement of the PS landmark.

Anterior Inferior Margin of C2 and C7 vertebral bodies
______________________________________________________

For C2 and C7, place the landmarks on each vertebrae at the most anterior and inferior point of the vertebral body in the anatomical midsagittal plane of the respective vertebral body.

.. figure:: docs/AI.PNG
       :scale: 75%
       :alt: This figure provides visual example of the placement of the AI landmark.


Measurements
------------

This protocol utilizes 17 measurements to quantify head position.  These measure assess both the face plane and the neck position inorder to predict if a image is in a flexed, neutral, or extended position. 


Head Measures or Face Plane Measures
____________________________________

ANS-PNS Plane
+++++++++++++

The angle of the nasal spine plane defined by the anterior nasal spine (ANS, 1) and the posterior nasal spine (PNS, 2) landmarks subtended with the horizontal plane of the imaging study.

.. figure:: docs/ANSPNS.PNG
       :scale: 75%
       :alt: This figure provides visual example of the ANS-PNS plane angle.


Maxillo-Pharyngeal Angle
++++++++++++++++++++++++

The angle of intersection between the PNS (2) - anterior tubercle of C1 (AT1, 6) line and the AT1 (6) - anterior inferior point of C2 (C2ai, 13) line.

.. figure:: docs/MP.PNG
       :scale: 75%
       :alt: This figure provides visual example of the MP angle.


C2 Angle
++++++++

The angle of intersection between the posterior border of C2 (C2pi, 7; PSA, 5) line and the ANS (1) - PNS (2) plane.

.. figure:: docs/C2.PNG
	:scale: 75%
	:alt: This figure provides visual example of the C2 angle.


Modified Bhalala head tilt angle
++++++++++++++++++++++++++++++++

The angle of intersection between the PNS (2) - opisthion (OPI, 3) line and the OPI (3) - C7 spinous process (SpPro7, 4) line.

.. figure:: docs/Bhalala.PNG
        :scale: 75%
        :alt: This figure provides visual example of the modified Bhalala angle.


Neck Measures
_____________


Antero-Posterior Measures
+++++++++++++++++++++++++

The anterior and posterior distances are calculated between the inferior landmarks of C2 to C7 and used for two of the head position measures.

.. figure:: docs/APDist.PNG
       :scale: 75%
       :alt: This figure provides visual example of the Anterior and Posterior distances.

Antero-Posterior Distance Ratio
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The ratio of the anterior to the posterior distances from the inferior borders of C2 to C7.


Antero-Porsterio Distance Difference
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The difference between the anterior and posterior distances from the inferior borders of C2 to C7.


Various Lower Cervical Spine Angle
++++++++++++++++++++++++++++++++++

The lower cervical spine has been measured using various combinations of landmarks.  This protocol includes five variations allowing the complexity of neck mobility to be assessed. Each variation is calculated at the angle of intersection between the ANS-PNS plane with the posterior boarder of the cervical vertebrae defined as follows:


C7 angle
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
For this variation the posterior border is defined by the posterior inferior of C7 to the posterior superior of C7.

.. figure:: docs/C7PS.PNG
	:scale: 75%
	:alt: This figure provides visual example of the C7 PI-PS angle.


C7-C6 angle
~~~~~~~~~~~~~~~~~~~~~~~~~~~
For this variation the posterior border is defined by the posterior inferior of C7 to the posterior inferior of C6.

.. figure:: docs/C76i.PNG
	:scale: 75%
	:alt: This figure provides visual example of the C7pi to C6pi angle.


C7-C5 angle
~~~~~~~~~~~~~~~~~~~~~~~~~~~
For this variation the posterior border is defined by the posterior inferior of C7 to the posterior inferior of C5.

.. figure:: docs/C75i.PNG
        :scale: 75%
        :alt: This figure provides visual example of the C7pi to C6pi angle.


C7-C4 angle
~~~~~~~~~~~~~~~~~~~~~~~~~~~
For this variation the posterior border is defined by the posterior inferior of C7 to the posterior inferior of C4.

.. figure:: docs/C74i.PNG
        :scale: 75%
        :alt: This figure provides visual example of the C7pi to C6pi angle.


C6-C4 angle
~~~~~~~~~~~~~~~~~~~~~~~~~~~
For this variation the posterior border is defined by the posterior inferior of C6 to the posterior inferior of C4.

.. figure:: docs/C64i.PNG
        :scale: 75%
        :alt: This figure provides visual example of the C7pi to C6pi angle.

 

Upper and lower cervical spine difference
_________________________________________


The change in angles along the cervical spine assist with determining the neck position.  Following are multiple angle difference measures.


C2vC7 difference
++++++++++++++++++++++++++++++

This measure calculates the difference between the C2 angle and C7pi-C7ps angle.


C2vC7-C6 difference
++++++++++++++++++++++++++++++

This measure calculates the difference between the C2 angle and C7pi-C6pi angle.


C2vC7-C5 difference
++++++++++++++++++++++++++++++

This measure calculates the difference between the C2 angle and C7pi-C5pi angle.


C2vC7-C4 difference
++++++++++++++++++++++++++++++

This measure calculates the difference between the C2 angle and C7pi-C4pi angle.


C2vC6-C4 difference
++++++++++++++++++++++++++++++

This measure calculates the difference between the C2 angle and C6pi-C4pi angle.


