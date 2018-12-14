Overview
========

The following documentation provides a protocol and the necessary files to apply two hybrid predictive models use GUIDE forest to classify a medical imaging study as flexion, neutral, or extension based on 17 head position measures.

Background
----------
The `Vocal Tract Development Lab <http://www.waisman.wisc.edu/vocal>`_ at the Waisman Center developed a protocol that classifies head position in medical images (CT/MRI) as flexed, neutral, or extended. Confidently classifying head position is vital to conducting analysis of the head and neck. Through the development of this protocol the impact of the dynamic and potential dichonomy of head and neck mobility more than one measure has been found to more reliabily classify head position.  The following protocol utilizes 17 measurements of the head and neck.  Additionally, this protocol entails two models that each have two steps. The fist step identifies most of the extension cases, while the second step classifies the remaining imaging studies as flexion, neutral, or extension. Each hybrid model was developed to approach neutral differently; model one focuses on neutral precision while model two focuses on neutral sensitivity. When the two models do not agree it is possible to identify boarderline cases, ex. neutral-flexed or neutral-extension.

General
-------
The training dataset for each step that includes GUIDE forest consists of MRI scans from six participants in five different head positions; extension, flexion, neutral with open mouth, neutral with closed mouth, and neutral with standardized open mouth.  All scans were collected prospectively at University of Wisconsin Hospital and Clinics.

The development and validation of this head position classification protocol has been submitted to Orthodontics & Craniofacial Research. The article can be accessed `here <http://>`_.


