
# Helmet Detection Deep Learning Project

This repository contains a deep learning project focused on detecting whether a person is wearing a helmet or not. The goal is to leverage machine learning techniques to automate helmet detection, which can be useful in enforcing safety regulations in various industries such as construction or motorcycling.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Training](#training)
- [Testing](#testing)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project uses deep learning models to detect helmets in images and videos. It includes custom scripts for image pre-processing, training, and testing the models. The model can be used to detect helmets in real-time scenarios or from pre-recorded footage.

## Project Structure
The repository is organized as follows:

```plaintext
├── cfg/                      # Configuration files for the model
├── data/                     # Dataset and annotations
├── output/                   # Model outputs (e.g., trained weights, logs)
├── utils/                    # Utility scripts for data processing
├── detect.py                 # Script for detecting helmets in images/videos
├── filename_copy.py          # Utility for managing file names
├── image2frame.py            # Script to convert video to frames for analysis
├── models.py                 # Deep learning model architecture
├── requirements.txt          # Required Python packages
├── shuffle.py                # Utility script for shuffling dataset
├── test.py                   # Script for testing the model
├── train.py                  # Script for training the model
└── README.md                 # Project documentation
```

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Debashish256/Helmet-Detection.git
   cd Helmet-Detection
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
### Helmet Detection
You can use the `detect.py` script to perform helmet detection on images or videos.

Example command:
```bash
python detect.py --input /path/to/input --output /path/to/output
```

This will process the input (image/video) and save the output with helmet detection results.

## Training
To train the model, use the `train.py` script. Make sure your dataset is properly set up in the `data/` directory.

Example command:
```bash
python train.py --config cfg/your_config_file.cfg --data data/your_data_file.yaml
```

The training results (e.g., trained weights, logs) will be saved in the `output/` directory.

## Testing
To evaluate the model on the test dataset, use the `test.py` script.

Example command:
```bash
python test.py --config cfg/your_config_file.cfg --weights output/your_trained_weights.pth
```

The evaluation results will be displayed in the terminal and saved in the `output/` directory.

## Results
The model performance will be reported in terms of accuracy, precision, recall, and other relevant metrics. Visual results will be saved in the `output/` directory.

## Contributing
Contributions are welcome! Please submit a pull request or create an issue to discuss any changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Author**: Debashish Behera  
**Email**: [debasisb582@gmail.com](mailto:debasisb582@gmail.com)
```

### Explanation:
1. **Introduction**: Brief introduction about the project's purpose.
2. **Project Structure**: Provides an overview of the directory structure.
3. **Installation**: Instructions to set up the project locally.
4. **Usage**: How to run the detection script.
5. **Training**: Instructions for training the model.
6. **Testing**: How to evaluate the model's performance.
7. **Results**: Where the results will be saved.
8. **Contributing**: Encourages contributions.
9. **License**: Mentions the license under which the project is released.

Feel free to adjust any sections as needed based on the specific details of your project.

![Result](https://user-images.githubusercontent.com/6930097/130743558-46887d57-4603-4522-ae02-7bb8cc6598b4.jpg)

Parameters on how good the model is in identifying the objects trained. 

![download](https://user-images.githubusercontent.com/6930097/130744000-e60129bf-88d1-455c-9095-1a0d4c908d55.png)


