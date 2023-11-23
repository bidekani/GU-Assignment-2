Demo 1 – Cats and Horses
 

Part 1 – Transformers and Image Classification (7 points)
Here we want to compare how Transformers perform when compared to other kinds of networks for image classification, such as CNNs. Follow the tutorial hereLinks to an external site. in order to implement an image classification model.

The tutorial uses a model called ViT (Visual Transformer), which was the first transformer model to perform better at image classification than a CNN did.

As much as the tutorial would like you to login and upload your model to their hub, you do not need to do so for this assignment.

 

Part 2 – Using the COCO dataset (8 points)
The HuggingFace tutorial uses one of the datasets in its datasets package. We would like it to be able to be used with the data that we were using in our demo notebook.

Create/modify your own dataloader so that we can use the ViT model to differentiate the cats and horses found in the COCO dataset (i.e. the one from the demo notebook).

 

Part 3 – Multiclass Classification (8 points)
The original task was only with binary classification. Get it to do multiclass classification, preferably on similar kinds of targets (like the cats and horses example, as opposed to cats and airplanes). You can find a list of categories for the dataset hereLinks to an external site..

Do this both for the original CNN model and for the ViT model.

 

Part 4 – How does the classification work now? (7 points)
Do a comparison of the models, both quantitative and qualitative. How does the models’ performances vary from each other? Is one of the models better at specific things than the other? Or is one of them much better than the other? Moreover, are these differences the same between both the binary classification task and in a multiclass classification task?