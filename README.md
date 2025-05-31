# Final Project: Colon Cancer Detection with Deep Learning

This application uses a deep learning model to assist in the detection of colon cancer from histopathological images. The model is based on a pre-trained **InceptionV3** architecture adapted for this task.

## Table of Contents

- [Description](#description)
- [Requirements](#requirements)
- [Installation](#installation)
- [Execution Instructions](#execution-instructions)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributions](#contributions)
- [License](#license)

## Description

The main objective of this project is to facilitate the early diagnosis of colon cancer through the automatic analysis of medical images using convolutional neural networks (CNN). The application includes an interactive dashboard developed with Streamlit to visualize and analyze the results.

## Requirements

- Python 3.8 or higher
- Jupyter Notebook or Google Colab
- Streamlit
- Dependencies listed in `requirements.txt`

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/JonesProgrammer/Final_Project.git
   cd Final_Project
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Execution Instructions

1. Open and run the `.ipynb` file in Jupyter Notebook or Google Colab, following the order of the cells.

2. Once finished, navigate in the terminal to the folder where `Dashboard.py` is located.

3. Launch the dashboard with Streamlit:
   ```bash
   streamlit run Dashboard.py
   ```

4. Open the indicated local address in your browser to view the results.

## Project Structure

```
├── Dashboard.py           # Interactive dashboard with Streamlit
├── requirements.txt       # List of dependencies
├── ...                    # Other scripts and files
└── README.md
```

## License

This project is under the MIT license. See the LICENSE file for more details.
