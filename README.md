# Image-Classification

Implemented #1 - Image Classification Test

Class labels are assigned as follows:
"spleen" - 0
"small_intestine" - 1
"skin_2" - 2
"skin_1" - 3
"pancreas" - 4
"lymph_node" - 5
"lung" - 6
“liver" - 7
"kidney" - 8
"endometrium_2" - 9
"endometrium_1", 10
"colon" - 11

Implemented image classification using three models in tensor flow: 
Model-1 using sequential neural network from scratch.
Model-2 using VGG16 pre-trained model.
Model3 - using CNN 

Plotted tSNE for train and test dataset.
Visualized tSNE at each layer.
Visualized the classification for top 10 predictions of each class.

Calculated training and testing accuracy for the dataset.
Plotted accuracy over the iterations.

We can see that tSNE performs better as we take output of deeper layers, this is because the output of every layer is keep getting refined to represent some class. So, this way the later layers adjusts according to the dataset. Thus, we can see the distinction of cluster(class) is very clear in last layer. tSNE can associate the distance similarity between the samples.

Image classification works accurately when the classes of images are clearly separated. In case of this dataset, the line of demarcation is not clear, which can increase the chances of misclassification. Overfitting and underfitting; bias-variance tradeoff, lead to decrease in accuracy.
More number of iterations, as we can see in the first model, the accuracy was high at lesser iterations.
