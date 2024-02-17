# Task_1_Translation

Demo Video link   https://drive.google.com/file/d/1-9WgZt71G7oIyHBfZBB3K_EwpyWXU8KI/view?usp=sharing


For installing tkinter in OPENAI folder
```bash
pip3 install Tk interface
```


Translate_my_text : This is a simple web application built with Streamlit and tkinter that allows users to translate text between different languages using OpenAI's GPT-3.5 language model.
OPENAI : This is a simple GUI application built using Python's Tkinter library and the OpenAI API to perform multilingual translations. The application allows users to input text, select source and target languages, and then translates the text accordingly.

Deep_Translator : This is using pyton tool in which we provide text , source language and target language. All instructions are given in notebook of this folder

### Installation

To run this application locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

3. Obtain an API key from OpenAI and save it in a file named `secret_key.py`. Example:

```python
# secret_key.py
openapi_key = "YOUR_OPENAI_API_KEY"
```

### Usage

To start the application, run the following command in your terminal:

```bash
streamlit run app.py
```

Once the application is running, you can:

- Enter the text you want to translate in the provided text area.
- Select the source language from the dropdown menu.
- Select the target language from the dropdown menu.
- Click on the "Translate" button to see the translated text.

### Supported Languages

The application supports translation between the following languages:

- English
- Hindi
- French
- Telugu
- Albanian
- Bengali
- Bhojpuri
- Brazilian Portuguese
- Chinese
- Dutch
- Georgian
- German
- Greek
- Gujarati
- Haryanvi
- Hungarian
- Indonesian
- Irish
- Italian
- Japanese
- Kannada
- Korean
- Maithili
- Mandarin Chinese
- Marathi
- Marwari
- Nepali
- Norwegian
- Oriya
- Portuguese
- Punjabi
- Romanian
- Russian
- Sanskrit
- Serbian
- Ukrainian
- Urdu

### Notes

- This application uses OpenAI's GPT-3.5 language model for translation.
- Ensure that you have a stable internet connection while using this application as it relies on OpenAI's API for translation.


