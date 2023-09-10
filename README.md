# PCB Defect Detection and Segmentation using SegFormer Architecture

The project is designed to detect and segment defects in PCBs (Printed Circuit Boards) utilizing the  SegFormer architecture,  aiming to enhance the quality standards in manufacturing processes. Project covers a series of steps such as data visualization, data preprocessing, model training, and inference.

## Installation
The project requires all the packages `requirements.txt` specified.


## Dataset

The dataset provided in the `data`[data] (https://github.com/nazlicanto/PCB-Defect-Detection-Segmentation/tree/main/data) folder, consists of images and their corresponding annotations in XML format. It provides mid & high-resolution images of PCBs and each of the annotated to indicate defects. 
For an in-depth understanding of the dataset & structures and to utilize it in different formats visit [Roboflow](https://universe.roboflow.com/diplom-qz7q6/defects-2q87r/dataset/16).

## Usage

1. Set up the environment and install the necessary packages. 
2. Import the required libraries. 
3. Define the data transformations and create a custom dataset class for loading the data. 
4. Set up the training arguments and define the metrics for evaluation.
5. Train the Segformer model using the Hugging Face's Trainer class.
6. Perform inference on the validation set and visualize the segmentation results.


#### The main Jupyter notebook containing all the scripts for the project: `defect_seg.ipynb`


## Results

The notebook includes, Visualizations: Defect Heatmap, Defect Size Distribution, examples of Segmented Outputs and the Model Outcomes.


## Demonstrations

#### Incorrect Installation Original - Masked 
![2](https://github.com/nazlicanto/PCB-Defect-Detection-Segmentation/blob/main/samples/1.png)

#### Short-Circuit Original - Masked 
![1](https://github.com/nazlicanto/PCB-Defect-Detection-Segmentation/blob/main/samples/2.png)


## Notes:
The model showcased in this project was trained on a relatively small dataset but still managed to achieve solid results. If you aim to further enhance the model's performance, consider:
- **Augmenting the Data**: Implement advanced data augmentation techniques such as rotations, zooming, and color jittering to artificially increase the dataset's size.
- **Fine-tuning**: Use a pre-trained model and fine-tune it on your specific dataset for better generalization.
- **Regularization**: Implement techniques like dropout or weight decay to prevent potential overfitting due to the smaller dataset size.





