# Handwritten Mathematical Expression Recognition

This project aims to develop an innovative encoder-decoder model for offline handwritten mathematical expression recognition, addressing the challenges of lack of temporal information and variability in writing styles. The model leverages cutting-edge technologies such as Vision Transformer (ViT) and Generative Pre-trained Transformer (GPT) to learn semantic-invariant features and generate coherent LaTeX code outputs.

## Features

- **Encoder-Decoder Architecture**: Utilizes a DenseNet encoder to extract semantic-invariant features from handwritten and printed expression images, combined with a transformer decoder for generating LaTeX code outputs.
- **State-of-the-Art Performance**: Achieves significant improvements in recognition rates over previous methods, evaluated on the CROHME dataset.
- **Robust to Diverse Writing Styles**: The model effectively handles variability in handwriting styles, a key challenge in offline handwritten mathematical expression recognition.
- **Adaptable to Multiple Domains**: The developed solution has potential applications in educational platforms, scientific research, engineering, publishing, data analysis, and mathematical software development.

## Installation

1. Clone the repository:
```
git clone https://github.com/not-indro/HMER_MajorProject.git
```

2. Install the required dependencies:
```
pip install -r requirements.txt
```

## Usage

1. Prepare your handwritten mathematical expression images.
2. Run the recognition script:
```
python recognize.py --input_dir /path/to/input/images --output_dir /path/to/output/directory
```

The script will process the input images and generate the corresponding LaTeX code outputs in the specified output directory.

## Dataset

The project was trained and evaluated on the CROHME dataset, a widely-used benchmark for handwritten mathematical expression recognition. The dataset is available for download [here](http://www.iapr-tc11.org/mediawiki/index.php/CROHME:_Competition_on_Recognition_of_Online_Handwritten_Mathematical_Expressions).

## Results

On the CROHME 2019 test set, our model achieved a BLEU score of 0.7542, improving the latest results by approximately 4% and enhancing the expression recognition rate compared to previous studies.

## Contributing

Contributions are welcome! If you have any ideas, improvements, or bug fixes, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
