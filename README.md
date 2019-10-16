OpenSource Assignment3
===

Sejong University 17011635 곽지훈

I used [this](https://github.com/llSourcell/antivirus_demo) code

I used malware.exe file as a malicious file.

And I used calc.exe as a normal file

learning
--
`$ python learning.py 
Researching important feature based on 54 total features

/home/duckji/.local/lib/python2.7/site-packages/sklearn/ensemble/forest.py:246: FutureWarning: The default value of n_estimators will change from 10 in version 0.20 to 100 in 0.22.
  "10 in version 0.20 to 100 in 0.22.", FutureWarning)
12 features identified as important:
1. feature DllCharacteristics (0.132443)
2. feature Subsystem (0.119511)
3. feature VersionInformationSize (0.114766)
4. feature SectionsMaxEntropy (0.097140)
5. feature ResourcesMaxEntropy (0.059155)
6. feature Machine (0.050932)
7. feature SectionsMinEntropy (0.047221)
8. feature Characteristics (0.044125)
9. feature MajorSubsystemVersion (0.042565)
10. feature ImageBase (0.039678)
11. feature MajorOperatingSystemVersion (0.037950)
12. feature SizeOfOptionalHeader (0.037856)

Now testing algorithms
GNB : 70.065194 %
DecisionTree : 98.971387 %
RandomForest : 99.373415 %
AdaBoost : 98.681637 %
GradientBoosting : 98.801159 %

Winner algorithm is RandomForest with a 99.373415 % success
Saving algorithm and feature list in classifier directory...
Saved
False positive rate : 0.506591 %
False negative rate : 0.907441 %`
