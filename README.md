# Bank Cheque MICR Data Extraction

This repository contains code for extracting Magnetic Ink Character Recognition (MICR) data from bank cheques. It includes a Jupyter Notebook for preprocessing the extracted data and an application built using Streamlit for interactive MICR data extraction.

## Purpose

The purpose of this repository is to provide a tool for automatically extracting MICR data from bank cheques, which can be useful for various banking and financial applications.

## Contents

- `preprocessing.ipynb`: Jupyter Notebook for preprocessing the extracted MICR data.
- `app.py`: Streamlit application for interactive MICR data extraction.
- `requirements.txt`: List of dependencies required to run the application.

## Usage

1. **Clone the Repository**: Clone this repository to your local machine.
2. **Install Dependencies**: Install the required dependencies using `pip install -r requirements.txt`.
4. **Preprocess Data**: Use the `preprocessing.ipynb` notebook to preprocess the extracted data as needed.
5. **Interactive Data Extraction**: Run the Streamlit application using `streamlit run app.py` and interactively extract MICR data from bank cheques, by installing the prepocessed data.

## Dependencies

- Python 3.x
- Jupyter Notebook
- Streamlit
- OpenCV
- NumPy
- Pillow
- scikit-image
- TensorFlow
- Matplotlib
- imutils

## Contributing

Contributions are welcome! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
