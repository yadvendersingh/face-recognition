# face-recognition

This project is a face recognition system that uses MTCNN and FAISS vector indexing to identify and recognize faces in images. The system is built using Python and various libraries such as facenet_pytorch, matplotlib and FAISS.

## Description

The face recognition system works by detecting faces in an image, extracting facial embeddings, and comparing them to a database of known faces. The system can be used for various applications such as security, attendance tracking, and more.

## How to Run the Project

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/yadvendersingh/face-recognition.git
    cd face-recognition
    ```

2. **Install Dependencies:**
    Make sure you have Python installed. Then, install the required libraries using pip:
    ```bash
    pip install -r requirements.txt
    ```

3. **Prepare the Dataset:**
    Place your images in the `dataset` directory. The images should be organized in subdirectories named after the person in the image.

4. **Run the Jupyter Notebook:**
    Open the `face_recognition.ipynb` notebook in Jupyter and run the cells to generate and store embeddings to perform face recognition.
    ```bash
    jupyter notebook face_recognition.ipynb
    ```

## Features

- Detects faces in images using MTCNN.
- Extracts Face embeddings using the MTCNN and store it into FAISS index.
- Compares faces to a database of known faces in FAISS.

## Requirements

- Python 3.12
- facenet_pytorch
- FAISS
- Matplotlib
- PIL
- Jupyter Notebook (for running the notebook)

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.