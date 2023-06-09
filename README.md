# Artwork Object Detection
## CSE252D

## Data 
https://drive.google.com/drive/folders/16WIiN5CixnSXvhi1BG_-zV5sGd5Gp031?usp=sharing


**In order to run our notebooks, open the google drive link above in your Google Drive. From your "Shared With Me" folder, click "Add a shortcut" option, and add a shortcut to "My Drive". That way you will be able to access the dataset and run the code.

## Models 

### SegFormer  
Open the file segFormer_final.ipynb in Google Colab. 

Testing:
To test a previously trained model, simply run all of the code blocks except the code blocks under the section "Train". The code blocks under the section "Load model and Test" should test the loaded model. 

Training: 
To train your own model, simply execute the code blocks in order and specify your desired hyperparameters (i.e. number of features, batch size, epochs)

### UNet 
Our main model is the SegFormer model, but we include our U-Net model as well. Open the file UNET_final.ipynb in Google Colab. Simply execute the code blocks in order to train and test the model. In order to only test a previously trained model simply skip the section "Run training"

### DeepLabv3+
Our main model is the SegFormer model, but we include our DeepLabv3+ model as well. Open the file UNET_final.ipynb in Google Colab. Simply execute the code blocks in order to train and test the model. In order to only test a previously trained model simply skip the section "Run training".






## References 
1. Kadish, David, Sebastian Risi, and Anders Sundnes Løvlie. "Improving object detection in art images using only style transfer." In 2021 International Joint Conference on Neural Networks (IJCNN), pp. 1-8. IEEE, 2021.
2. Huang, Xun, and Serge Belongie. "Arbitrary style transfer in real-time with adaptive instance normalization." In Proceedings of the IEEE international conference on computer vision, pp. 1501-1510. 2017.
3. Xie, Enze, Wenhai Wang, Zhiding Yu, Anima Anandkumar, Jose M. Alvarez, and Ping Luo. "SegFormer: Simple and efficient design for semantic segmentation with transformers." Advances in Neural Information Processing Systems 34 (2021): 12077-12090.
4. Chen, Liang-Chieh, Yukun Zhu, George Papandreou, Florian Schroff, and Hartwig Adam. "Encoder-decoder with atrous separable convolution for semantic image segmentation." In Proceedings of the European conference on computer vision (ECCV), pp. 801-818. 2018.
5. Robin Rombach, Andreas Blattmann, Dominik Lorenz, Patrick Esser, and Bj ̈orn Ommer. High-resolution image synthesis with latent diffusion models,
6. Guerrie, Paul. “How to Train Segformer on a Custom Dataset.” Roboflow Blog, 25 July 2022, blog.roboflow.com/how-to-train-segformer-on-a-custom-dataset-with-pytorch-lightning/. 
