# PIIDataMask
Masking PII Data with OCR and NLP
Detailed Steps
1. Manually Download spaCy Model
You can manually download the spaCy model using the following command:

bash
Copy code
python -m spacy download en_core_web_sm
Alternatively, you can download the model from the spaCy GitHub repository and install it manually.

2. Ensure Installation of Dependencies
Make sure all necessary libraries (easyocr, pdf2image, presidio-analyzer, spacy, Pillow, and certifi) are installed:

bash
Copy code
pip install easyocr pdf2image presidio-analyzer spacy Pillow certifi

3. Update the Code to Load the spaCy Model Locally
Here's the complete and corrected script to handle the text extraction, PII detection, and masking using easyocr, presidio-analyzer, and spaCy with manual model loading:

