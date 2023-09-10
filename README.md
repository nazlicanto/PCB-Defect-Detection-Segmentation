# PCB-Defect-Detection-Segmentation
PCB defect detection and segmentation using SegFormer architecture

# PCB-Defect-Detection-Segmentation

Leveraging the SegFormer architecture, this project aims to identify and segment defects in PCBs, fostering higher standards in manufacturing processes. steps including data visualization, data preprocessing, model training, and inference.


## Installation
The project requires all the packages `requirements.txt` specified.


## Dataset

The dataset consists of images and their corresponding annotations in XML format. The dataset provides mid & high-resolution images of PCBs and each of the annotated to indicate defects. 
For an in-depth understanding of the dataset & structures and utilize it in different formats visit Roboflow: [Dataset](https://universe.roboflow.com/diplom-qz7q6/defects-2q87r/dataset/16) 

## Usage

Set up the environment and install the necessary packages. 
Import the required libraries. 
Define the data transformations and create a custom dataset class for loading the data. 
Set up the training arguments and define the metrics for evaluation.
Train the Segformer model using the Hugging Face's Trainer class.
Perform inference on the validation set and visualize the segmentation results.

## `defect_seg.ipynb:` The main Jupyter notebook containing all the scripts for the project.

## Results

The results section will include visualizations such as the defect heatmap, defect size distribution, and examples of segmented outputs.


## Demonstrations

### Short-Circuit Original - Masked 

### Incorrect Installation Original - Masked 


## Notes:
The model showcased in this project was trained on a relatively small dataset but still managed to achieve solid results. If you aim to further enhance the model's performance, consider:
- **Augmenting the Data**: Implement advanced data augmentation techniques such as rotations, zooming, and color jittering to artificially increase the dataset's size.
- **Fine-tuning**: Use a pre-trained model and fine-tune it on your specific dataset for better generalization.
- **Regularization**: Implement techniques like dropout or weight decay to prevent potential overfitting due to the smaller dataset size.





