# Artwork Object Detection
## CSE252D

## Data 
Original COCO Data: https://drive.google.com/file/d/1AbaaGUQSQYPzEJppEwl_RNMYf73lu4DV/view?usp=share_link

Stylized Data (cocoStyle): https://drive.google.com/file/d/1JGJ78FqcwEvTayuFj4giH7J63UOCF2sw/view?usp=share_link

Roboflow Data (subset of cocoStyle + custom test set): https://universe.roboflow.com/252/people-in-art


**In order to run our notebooks, open the Stylized Data link in your Google Drive. From your "Shared With Me" folder, click "Add a shortcut" option on the zip file, and add a shortcut to "My Drive". That way you will be able to access the dataset and run the code without having to re-download the (very big) dataset**

## Models 

### UNet 


### DeepLabv3+


### SegFormer 

Data: 
This model accesses our dataset stored in Roboflow so there is no need to add anything to your Google Drive. If you would like to run the model on a different Roboflow dataset please change the API key when importing the data. 

Training: 
To train your own model, simply execute the code blocks in order and specify your desired hyperparameters (i.e. number of features, batch size, epochs)

Testing:


## References 
1. Kadish, David, Sebastian Risi, and Anders Sundnes Løvlie. "Improving object detection in art images using only style transfer." In 2021 International Joint Conference on Neural Networks (IJCNN), pp. 1-8. IEEE, 2021.
2. Huang, Xun, and Serge Belongie. "Arbitrary style transfer in real-time with adaptive instance normalization." In Proceedings of the IEEE international conference on computer vision, pp. 1501-1510. 2017.
3. Xie, Enze, Wenhai Wang, Zhiding Yu, Anima Anandkumar, Jose M. Alvarez, and Ping Luo. "SegFormer: Simple and efficient design for semantic segmentation with transformers." Advances in Neural Information Processing Systems 34 (2021): 12077-12090.
4. Chen, Liang-Chieh, Yukun Zhu, George Papandreou, Florian Schroff, and Hartwig Adam. "Encoder-decoder with atrous separable convolution for semantic image segmentation." In Proceedings of the European conference on computer vision (ECCV), pp. 801-818. 2018.
5. Guerrie, Paul. “How to Train Segformer on a Custom Dataset.” Roboflow Blog, 25 July 2022, blog.roboflow.com/how-to-train-segformer-on-a-custom-dataset-with-pytorch-lightning/. 
