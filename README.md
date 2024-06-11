# DeepGlobe-Land-Cover-Classification-with-DeepLabV3-Training-and-Evaluation-Pipeline


This repository contains code for training and evaluating a land cover classification model using the DeepGlobe dataset. The model is implemented using the DeepLabV3+ architecture with a ResNet50 backbone.

## Dataset

The DeepGlobe dataset is used for training and validation. It consists of satellite images and corresponding segmentation masks for land cover classes.

## Setup

1. Clone the repository:

    ```bash
    git clone <repository-url>
    cd deepglobe-land-cover-classification
    ```

2. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the DeepGlobe dataset from [Kaggle](https://www.kaggle.com/) and place it in the `data` directory.

4. Run the provided notebook to train the model:

    ```bash
    jupyter notebook train_model.ipynb
    ```

## Usage

1. **Training:** Execute the training notebook (`train_model.ipynb`) to train the model on the DeepGlobe dataset. Adjust hyperparameters as needed.

2. **Evaluation:** Evaluate the trained model on the validation set to measure segmentation accuracy and other metrics.

## File Structure

- `train_model.ipynb`: Jupyter notebook for training the DeepLabV3+ model on the DeepGlobe dataset.
- `data/`: Directory to store the DeepGlobe dataset.
- `models/`: Directory to save trained models.
- `utils/`: Utility functions for data preprocessing, visualization, and evaluation.

## Results

After training, the model achieves an average IoU score of X.XX on the validation set.

## Credits

- This project is based on the DeepGlobe Land Cover Classification dataset available on Kaggle.
- The implementation utilizes the `segmentation_models_pytorch` library for deep learning model architectures.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
