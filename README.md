# THESIS-G56

1. Scratched CNN:

AdaBoost accuracy: 0.9616666666666667, log loss: 0.6799512961566305
KNN accuracy: 0.925, log loss: 0.5082354852169635
RF accuracy: 0.9683333333333334, log loss: 0.2007175202223789
SVM accuracy: 0.9116666666666666, log loss: 0.2125816734773097
Softmax accuracy: 0.8516666666666667, log loss: 0.3311791703391175

Average Accuracy: 0.9236666666666666
Average Log Loss: 0.38653302908248


2. Xception: *******
AdaBoost accuracy: 0.9283333333333333, log loss: 0.6792333291086965
KNN accuracy: 0.9633333333333334, log loss: 0.2038500659720539
RF accuracy: 0.955, log loss: 0.24816358367439592
SVM accuracy: 0.965, log loss: 0.08809882456123996
Softmax accuracy: 0.9166666666666666, log loss: 0.2133377603045656

Average Accuracy: 0.9456666666666667
Average Log Loss: 0.28653671272419035


3. InceptionV3: *******

AdaBoost accuracy: 0.92, log loss: 0.6817462596309758
KNN accuracy: 0.9533333333333334, log loss: 0.14603454441031466
RF accuracy: 0.96, log loss: 0.2582967307641034
SVM accuracy: 0.975, log loss: 0.07666348533989853
Softmax accuracy: 0.915, log loss: 0.23643664157851088

Average Accuracy: 0.9446666666666668
Average Log Loss: 0.2798355323447606

4. ResNet50:

AdaBoost accuracy: 0.865, log loss: 0.6871645836798073
KNN accuracy: 0.8983333333333333, log loss: 0.6072289523423297
RF accuracy: 0.9266666666666666, log loss: 0.2952595854536777
SVM accuracy: 0.8533333333333334, log loss: 0.34704309463142663
Softmax accuracy: 0.8016666666666666, log loss: 0.45489244385965244

Average Accuracy: 0.869
Average Log Loss: 0.47831773199337874


5. EfficientNetB0:  *******

AdaBoost accuracy: 0.9733333333333334, log loss: 0.6746284609535165
KNN accuracy: 0.9866666666666667, log loss: 0.15425540876152485
RF accuracy: 0.9716666666666667, log loss: 0.21440771800911676
SVM accuracy: 0.995, log loss: 0.026809050852255028
Softmax accuracy: 0.9616666666666667, log loss: 0.10126744273189626

Average Accuracy: 0.9776666666666667
Average Log Loss: 0.23427361626166188


6. VGG19: 

AdaBoost accuracy: 0.8433333333333334, log loss: 0.6885105531247203
KNN accuracy: 0.865, log loss: 0.862328129818434
RF accuracy: 0.935, log loss: 0.27497225916235635
SVM accuracy: 0.7933333333333333, log loss: 0.4468341263052535
Softmax accuracy: 0.775, log loss: 0.5123064130757691

Average Accuracy: 0.8423333333333334
Average Log Loss: 0.5569902962973066



1. InceptionV3 + EfficientNetB0     => 	Average Accuracy: 0.9356666666666668    ************
					Average Log Loss: 0.37527989950583746
2. EfficientNetB0 + Xception        => 	Average Accuracy: 0.8499999999999999
					Average Log Loss: 0.5304190772282774
3. InceptionV3 + Xception           => 	Average Accuracy: 0.9493333333333333    ************
					Average Log Loss: 0.28463496868478366


1. InceptionV3 + EfficientNetB0 + InceptionV3 + Xception  => Average Accuracy: 0.932
							     Average Log Loss: 0.38647054195308417
