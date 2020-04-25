dataset
https://drive.google.com/file/d/1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK/view


Vgg16
Epoch=5
lr=0.001, momentum=0.9
All the fc layers were removed and two were added the first fc layer has neurons according to formula which is 360 and then activation function relu and then output classes

Confusion Matrix Test
583 , 32
13 , 872

Confusion Matrix Train
551 , 89
19 , 845

Confusion Matrix Validation
535 , 80
68 , 817


Accuracy on test=97 %
F1 score=0.9628


resNet
Epoch=5
lr=0.001, momentum=0.9
All the fc layers were removed and two were added the first fc layer has neurons according to formula which is 360 and then activation function relu and then output classes

Confusion Matrix Test
573 , 42
24 , 861

Confusion Matrix Train
568 , 73
69 , 794

Confusion Matrix Validation
552 , 63
81 , 804


Accuracy Test=: 95 %
F1 score=0.945


Task 2 vgg16 with all layers trained
Epoch=3
lr=0.001, momentum=0.9

Confusion Matrix Test
601 , 14
79 , 806

Confusion Matrix Train
573 , 47
94 , 790

Confusion Matrix Validation
581 , 34
171 , 714


Accuracy = 93%
F1 score=0.9281



Task 2 resnet with all layers trained
Epoch=3
lr=0.001, momentum=0.9


Confusion Matrix Test
554 , 61
12 , 873

Confusion Matrix Validation
504 , 111
51 , 834

Confusion Matrix Train
504 , 96
35 , 869


Accuracy = 95 %
F1 score=0.9421
