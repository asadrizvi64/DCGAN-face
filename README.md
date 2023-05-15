# Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks (DCGAN)
This tutorial demonstrates how to implement a DCGAN architecture in PyTorch to generate new images that look similar to the images in the training set. The code is based on the paper "Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks" by Radford et al.

## Getting Started
### Prerequisites
- Python 3.6 or higher
- PyTorch 1.8.0 or higher
- NumPy, Matplotlib, and Pillow libraries

### Installation
1. Clone the repository:
```bash
git clone https://github.com/your_username/dcgan-tutorial.git
```
2.Install the required libraries:
```bash
pip install -r requirements.txt
```

### Usage
1. Run the train.py script to train the model:
```bash
python train.py
```
2. The generated images will be saved in the generated_images/ folder.
3. Run the generate.py script to generate new images:
```bash
python generate.py --num_images 10
```
4. The generated images will be saved in the generated_images/ folder.

### Structure
The project has the following structure:
```.
├── data/                   # Contains the training data
│   └── <dataset_name>/
│       └── <train_images>.jpg
├── generated_images/       # Contains the generated images
├── models/                 # Contains the generator and discriminator models
│   ├── generator.py
│   └── discriminator.py
├── utils/                  # Contains utility functions for loading data and images
│   ├── data_loader.py
│   └── image_utils.py
├── train.py                # Script for training the model
├── generate.py             # Script for generating new images
├── requirements.txt        # Contains the required libraries
└── README.md               # This file
```

### Contributing
Contributions are welcome! If you find any bugs or have suggestions for improving the code, please open an issue or create a pull request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.
