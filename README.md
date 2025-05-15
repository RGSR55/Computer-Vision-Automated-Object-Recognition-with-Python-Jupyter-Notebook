# Resume
There is a growing trend in the use of AI methods, especially for tasks like object recognition. However, it's important to critically assess their indiscriminate use, particularly in cases where traditional methods offer effective and efficient solutions with lower computational requirements and simple and fast implementation.  

This work presents an automated robust traditional method focused on the ability to detect, analyze, and classify multiple objects within images. Object detection and classification are based on geometrical feature extraction. The system is designed to reliably identify objects in a dataset consisting of 40 evaluation images under varying lighting and noise conditions.  

To achieve this, several preprocessing techniques are applied, such as gamma correction, morphological operations and noise suppression, ensuring the effectiveness of dynamic adaptive binary. In this approach, the threshold determination is based on the local mean intensity calculated for each image segment, allowing better adaptability across different scenarios. Parameters like gamma correction and binary offset are automatically adjusted based on the average brightness of the image. 

The result of the segmentation process is a collection of blobs or contours that accurately delineate each object in the image. This is particularly valuable when extracting detailed geometric attributes of the objects. In the final step, the dataset images are annotated with the detected contours and labeled with their corresponding categories. 

The final object count and classification results are displayed in a dictionary format for easier analysis and evaluation.

As part of future work, I intend to extract invariant geometric features using Hu moments to enhance robustness to significant variations in scale, rotation, and translation, or potentially hybridize the method with a holistic approach.

## Examples

![1](https://github.com/user-attachments/assets/a5697962-eed5-4880-8183-d94266de62ef)
![2](https://github.com/user-attachments/assets/cb032cd5-4c48-4c5f-a945-13922c441869)
![3](https://github.com/user-attachments/assets/cb0d001d-0d41-4fe8-af0a-9c359a6ea41c)

## Usage

1. Clone this repository or download the following files
2. Install Anaconda Prompt
3. Set Up Conda Environment
4. Install the required dependencies  to run the Jupyter notebook
