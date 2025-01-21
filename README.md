# Knee Osteoarthritis Classification

This project involves the classification of knee osteoarthritis severity using deep learning techniques, particularly a ResNet model. It includes data preprocessing, model training, evaluation, and visualization of the results.

## Features

- **Data Preprocessing**: Loads and preprocesses images for knee osteoarthritis classification.
- **Custom Dataset Class**: Defines a custom PyTorch `Dataset` class for handling the knee dataset.
- **Model Training and Evaluation**: Utilizes a ResNet model to classify the severity of knee osteoarthritis and evaluates its performance through various metrics.
- **Visualization**: Uses Grad-CAM for interpretability of the model's predictions and confusion matrix visualization for performance evaluation.

## Project Structure

- `main.ipynb`: A Jupyter notebook that handles data loading, preprocessing, model training, evaluation, and visualization for knee osteoarthritis classification.

## Dependencies

- Python libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `torch`
  - `torchvision`
  - `PIL`
  - `scikit-learn`
  - `tqdm`
  - `opencv-python`

Install dependencies using:
```bash
pip install numpy pandas matplotlib seaborn torch torchvision Pillow scikit-learn tqdm opencv-python
```

## Usage

1. Open `main.ipynb` in a Jupyter Notebook environment.
2. Follow the cells to load and preprocess the dataset, define the model, and train it.
3. Evaluate the model's performance using accuracy, confusion matrix visualizations, and classification reports.
4. Utilize Grad-CAM for visual interpretability of the model's predictions.

### Example File Paths
- Image Dataset: Located in the `train` and `test` subdirectories.

## Notes

- Adjust the dataset paths and parameters as needed within the notebook.
- The dataset should be organized into class subdirectories within `train` and `test` folders for proper loading.

## License

This project is licensed under the MIT License. See the LICENSE file for details.


