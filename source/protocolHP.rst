

Head Position Protocol
======================


Necessary Files
---------------

The two hybrid head position models require specific files unique to each step: a descriptive text file, a cost matrix test file, a test input file, and a training data in a .csv file. The four files necessary for each step can be downloaded at below in the description to each step. Furthermore, to run this protocol you will need to download the GUIDE multi-purpose machine learning algorithm from `Dr Loh's website <http://www.stat.wisc.edu/~loh/guide.html>`_.



Head Position Model One
_______________________



Step One
++++++++

This Step identifies extended cases using the C7 PS to PI angle.  Identify all cases that have the C7 PS to PI angle greater than 118.425. These cases should be classified as extended and removed from the dataset before proceeding to step two.


Step Two
++++++++

This step identifies the remaing case as either flexed, neutral or extended using the GUIDE forest algorithm.

Download the following files:
	* Descriptive File :download:`txt <docs/Description1.txt>`
	* Cost Matrix File :download:`txt <docs/CostMatrix3x2.txt>`
	* Test Input File :download:`inp <docs/test1.inp>`
	* Training Data File :download:`csv <docs/Test.csv>`


Head Position Model Two
_______________________



Step One
++++++++

This step identified extended cases using the GUIDE forest method.  This step provides a yes or no answer whether each case is in extended or in another position. The cases which have an output of yes should be identified as extended and removed from the dataset before proceeding to step two. 

Download the following files:
        * Descriptive File
        * Cost Matrix File
        * Test Input File 
        * Training Data File 


Step Two
++++++++

This step identifies the remaining cases as either flexed, neutral, or extended using the GUIDE forest algorithm.


Download the following files
        * Descriptive File
        * Cost Matrix File
        * Test Input File
        * Training Data File



