# AI-Generated Text Detection

A language neural network (LNN) model designed to detect AI-generated text, utilizing fine-tuned BERT for enhanced identification of synthetic text content. This project features a user-friendly interface built with Streamlit, allowing for real-time analysis and demonstrating practical applications in content authenticity and moderation.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training and Fine-Tuning](#model-training-and-fine-tuning)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project implements a BERT-based neural network model to classify text as either AI-generated or human-written, achieving 90% accuracy through fine-tuning. This model can be deployed in various applications, such as content moderation and authenticity verification, to address concerns over AI-generated content.

## Features
- **Fine-Tuned BERT Model**: The core model is based on BERT, optimized to detect AI-generated text with high accuracy.
- **Real-Time Analysis**: Users can input text via a Streamlit interface and receive instant feedback on whether it is likely AI-generated or human-written.
- **Content Authenticity and Moderation**: Practical for platforms and applications that require verification of text authenticity.

## Installation

To install and set up the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/AI-Generated-Text-Detection.git
   cd AI-Generated-Text-Detection
   ```

2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Launch the Streamlit interface:**
   ```bash
   streamlit run app.py
   ```

2. **Enter text for analysis:**  
   Once the interface is running, input any text to see whether it is classified as AI-generated or human-written.

3. **Interpreting the Results:**  
   The model will provide a probability score and label indicating its confidence in the classification.

## Model Training and Fine-Tuning

The model was fine-tuned on a large dataset of AI-generated and human-written text using BERT. For additional training details, refer to the `train_model.py` script.

If you would like to retrain or fine-tune the model:
1. Prepare your dataset in the required format.
2. Run the training script:
   ```bash
   python train_model.py
   ```

## Results

The model achieved an accuracy of 90% on the test dataset. This performance level allows the model to be effective in distinguishing between AI-generated and authentic human content.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize each section according to your project specifics, such as adding details about your dataset or additional usage examples. Let me know if you need help with any adjustments!
