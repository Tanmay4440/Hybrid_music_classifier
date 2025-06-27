# Hybrid Music Classifier

A machine learning project for hybrid music classification. This repository provides tools and models to classify music tracks based on various audio features, leveraging both classical machine learning and deep learning techniques.

## Features

- Hybrid approach combining traditional ML and deep learning
- Audio preprocessing and feature extraction
- Model training and evaluation scripts
- Support for multiple genres and datasets

## Technologies Used

- Python
- Librosa
- Scikit-learn
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/Tanmay4440/Hybrid_music_classifier.git
    cd Hybrid_music_classifier
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Prepare your dataset and place it in the appropriate directory (see project documentation).
2. Run preprocessing and feature extraction:
    ```bash
    python preprocess.py
    ```
3. Train the model:
    ```bash
    python train.py
    ```
4. Evaluate or use the model for inference:
    ```bash
    python predict.py --input path_to_audio_file
    ```

## Example

```bash
python predict.py --input samples/song1.wav
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Author

- [Tanmay4440](https://github.com/Tanmay4440)

## License

This project is licensed under the MIT License.
