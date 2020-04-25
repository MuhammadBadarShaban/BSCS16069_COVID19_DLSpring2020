# BSCS16069_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

Task 01:

VGG16:
Training:
Accuracy of the network on the train images: 88 %
Confusion Matrix: array ([[4003, 916],
        	          [ 488, 6593]]),
 F1-Score: 0.8850260112589963
Validation:
Accuracy of the network on the validation images: 88 %
Confusion Matrix: array ([[514, 101],
        		  [ 68, 817]])
F1-Score: 0.8839292153114934
Testing:
Accuracy of the network on the test images: 94 %
Confusion Matrix: array ([[546, 69],
       			  [ 16, 869]]),
 F1-Score: 0.948744436110621

ResNet18:
Training:
Accuracy of the network on the train images: 84 %
Confusion Matrix: array ([[3768, 1151],
        		  [ 650, 6431]])
F1-Score: 0.8464574099067318 
Validation:
Accuracy of the network on the validation images: 83 %
Confusion Matrix: array ([[474, 141],
        		  [107, 778]]),
F1-Score: 0.8797366860521152
Testing:
Accuracy of the network on the test images: 90 %
Confusion Matrix: array ([[530, 85],
        		 [ 54, 831]]),
F1-Score: 0.9347149095475235

Task 02:

VGG16(all unfreeze):
Training:
Accuracy of the network on the train images: 92 %
Confusion Matrix: array ([[4169, 750],
        		 [ 168, 6913]])
F1-Score: 0.9450649417081887
Validation:
Accuracy of the network on the validation images: 91 %
(array([[516,  99],
        [ 34, 851]])
Confusion Matrix: array ([[516, 99],
        		 [34, 851]])
F1-Score: 0.9410218510526115

Testing:
Accuracy of the network on the test images: 96 %
Confusion Matrix: array ([[570, 45],
        	          [  4, 881]]),
F1-Score: 0.9735066812223391

ResNet18(all unfreeze):
Training:
Accuracy of the network on the train images: 91 %
Confusion Matrix: array ([[4283, 636],
        	          [ 344, 6737]])
F1-Score: 0.8908408693404202
Validation:
Accuracy of the network on the validation images: 90 %
Confusion Matrix: array ([[537, 78],
        	          [ 62, 823]])
F1-Score: 0.9525192547851113
Testing:
Accuracy of the network on the test images: 96 %
Confusion Matrix: array ([[575, 40],
        	          [ 14, 871]])
F1-Score: 0.9202959846947847

VGG16(last 10 layers freeze):
Training:
Accuracy of the network on the train images: 91 %
Confusion Matrix: array ([[3984, 935],
        	          [ 107, 6974]])
F1-Score: 0.9124263796045832)
Validation:
Accuracy of the network on the validation images: 90 %
Confusion Matrix: array ([[488,127],
        	          [ 21, 864]])
F1-Score: 0.9327960409065976
Testing:
Accuracy of the network on the test images: 96 %
Confusion Matrix: array ([[559, 56],
       			  [3, 882]])
F1-Score: 0.982442091802088

ResNet18(last layer freeze):
Training:
Accuracy of the network on the train images: 92 %
Confusion Matrix: array ([[4391, 528],
        	          [ 404, 6677]])
F1-Score: 0.9707587907581268
Validation:
Accuracy of the network on the validation images: 90 %
Confusion Matrix: array ([[542, 73],
       			  [ 72, 813]])
F1-Score: 0.9128628866516862
Testing:
Accuracy of the network on the test images: 96 %
Confusion Matrix: array ([[576, 39],
       			      [ 12, 873]])
F1-Score: 0.9892312249292441

VGG16(last 20 layers freeze):
Training:
Accuracy of the network on the train images: 92 %
Confusion Matrix: array ([[4156, 763],
        	          [ 144, 6937]]),
F1-Score: 0.8894895197098847
Validation:
Accuracy of the network on the validation images: 91 %
Confusion Matrix: array ([[521, 94],
        		  [ 37, 848]]))
F1-Score: 0.9495896288278434
Testing:
Accuracy of the network on the test images: 97 %
Confusion Matrix: array ([[574, 41],
        	          [ 4, 881]]),
F1-Score: 0.9562134256294978

ResNet18(2nd last and last layers freeze):
Training:
Accuracy of the network on the train images: 91 %
Confusion Matrix: array ([[4305, 614],
        	          [ 355, 6726]])
F1-Score: 0.9542740248618062
Validation:
Accuracy of the network on the validation images: 90 %
Confusion Matrix: array ([[542, 73],
       			  [ 66, 819]])
F1-Score: 0.8720088200765641
Testing:
Accuracy of the network on the test images: 96 %
Confusion Matrix: array ([[572, 43],
                          [ 17, 868]]),
F1-Score: 0.9710680488199116
