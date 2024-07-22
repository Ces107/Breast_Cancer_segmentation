# Breast Cancer Histology Image Segmentation

## Project Overview

This project focuses on the segmentation of patches of histology images of breast cancer. The goal is to develop and implement a machine learning model that can accurately segment and identify different tissue regions in histology images. This project can be beneficial for medical research and diagnostic purposes.

## Repository Contents

- `notebooks/`: Contains the Jupyter Notebook (`histology_image_segmentation.ipynb`) with the entire workflow for image segmentation.
- `README.md`: Overview of the project and instructions for setting up and running the code.

## Requirements

- Python 3.7+
- Jupyter Notebook
- TensorFlow 
- NumPy
- OpenCV
- Scikit-learn
- Matplotlib
- Pandas

## Dataset

The dataset used in this project consists of histology images of breast cancer.

## Jupyter Notebook

The main notebook for this project is `histology_image_segmentation.ipynb`. This notebook includes the following steps:

1. **Data Loading**: Load the histology images from the `data/` directory.
2. **Data Preprocessing**: Preprocess the images, including resizing, normalization, and data augmentation.
3. **Model Building**: Build a segmentation model using a neural network architecture suitable for image segmentation.
4. **Model Training**: Train the model on the preprocessed images.
5. **Model Evaluation**: Evaluate the model's performance using appropriate metrics.


## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. We welcome improvements, bug fixes, and new features.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

- [Dataset Source]:
  https://www.ncbi.nlm.nih.gov/pubmed/27563488
  http://spie.org/Publications/Proceedings/Paper/10.1117/12.2043872

For any questions or issues, please open an issue on GitHub or contact me at cesar0407p@gmail.com

Happy coding!
