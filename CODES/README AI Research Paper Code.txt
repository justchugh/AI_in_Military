
---------------------------

Input Version 01

Input Data: Raw image files of hand gestures.

Output Data: 'ProcessedImages.xlsx' with labeled images.

Purpose: This script is designed for the initial handling of raw image data of hand gestures. It processes these images by applying various preprocessing techniques to improve their quality and suitability for machine learning. The images are then labeled based on their corresponding hand gestures, preparing a structured dataset for subsequent machine learning applications.

---------------------------

Linker Version 01

- Input Data: Data from 'ProcessedImages.xlsx'.

- Output Data: 'LinkedData.xlsx' with interconnected data points.

- Purpose: This script acts as a bridge between initial data processing and advanced analysis. It takes the processed and labeled image data and creates associations or links between various data points. This is crucial for setting up a structured format that allows for more sophisticated analytical techniques to be applied, particularly in scenarios where understanding the relationship between different data elements is key.

---------------------------

Training Version 01:

- Input Data: Labeled data from 'LinkedData.xlsx'.

- Output Data: A trained machine learning model file.

- Purpose: The core focus of this script is on training a machine learning model, specifically a convolutional neural network, using the prepared and linked image data. It involves the application of advanced machine learning techniques to enable the model to accurately recognize and interpret hand gestures. This training process is fundamental for developing a robust model that can be used for practical applications in gesture recognition.

---------------------------