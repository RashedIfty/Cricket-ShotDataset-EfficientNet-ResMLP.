## Cricket Shot Dataset - EfficientNet + ResMLP

This GitHub repository comprises code for a comprehensive approach to classify cricket shot images using the EfficientNet and ResMLP (Residual Multi-Layer Perceptron) models.

### Overview:

The code contains functionality for:

1. **Data Handling:**
    - Iterating through the dataset directory structure to load and preprocess images for classification.
    - Creating train, validation, and test datasets using the `make_dataframes` function.
    - Generating image data generators (`make_gens`) for training and validation.

2. **Model Architectures:**
    - Implementation of the EfficientNet model (`EfficientNetModel`) using custom layers like MBConv and SEBlock.
    - Construction of a Residual MLP (`ResMLP`) model with specific block configurations.

3. **Training and Evaluation:**
    - Training the EfficientNet model and Residual MLP model using the `fit` method.
    - Evaluation metrics such as accuracy, AUC, and loss are computed and plotted for analysis.
    - Utilizing the `predictor` function to assess model performance on the test dataset, including confusion matrix and classification report generation.

### Key Features:

- Data loading, preprocessing, and splitting into train, test, and validation sets.
- Creation and training of EfficientNet and ResMLP models for cricket shot classification.
- Evaluation of models using performance metrics and visualization tools.
- Detailed analysis through classification reports and confusion matrices.

### Usage:

The provided code allows for experimentation with EfficientNet and ResMLP architectures for cricket shot classification. Users can:

- Modify model hyperparameters or architectures for improved performance.
- Explore augmentation techniques or other enhancements to further boost model accuracy.
- Expand the dataset or introduce transfer learning techniques for broader cricket shot classification.

Feel free to explore, enhance, or adapt this codebase for your cricket shot classification tasks!

For a detailed understanding and usage instructions, please refer to the code files available in this repository.

**Performance Summary:**
- The combined model achieved an accuracy of 83.33% on a test set consisting of cricket shot images, with detailed performance metrics provided in the classification report.

**Note:** Ensure the dataset directory structure and configurations align with the provided code for seamless execution.

For any questions or collaborations, please reach out through the repository's issues or contact information.

---

Adjust this description as needed to reflect any additional information or instructions specific to your repository and its usage.
