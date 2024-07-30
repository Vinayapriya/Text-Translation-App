# Text-Translate-App
# Language Translation App

A Streamlit application for translating text into various languages using `googletrans` and additional text processing with a custom `pathway` module.

## Features

- Translate text into multiple languages.
- Apply additional processing to the translated text using the custom `pathway` module.

 ## Demo
 [streamlit-app-2024-07-30-12-07-50.webm](https://github.com/user-attachments/assets/69aff1dd-6c4b-46c9-a818-05761f8f9733)


## Prerequisites

- Python 3.6 or later

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/language-translation-app.git
   cd language-translation-app

2. **Create and activate a virtual environment:**

On Windows:
  ```bash
   python -m venv venv
   .\venv\Scripts\activate
```
On macOS/Linux:
  ```bash
   python -m venv venv
   source venv/bin/activate
```
3. **Install the dependencies:**
  ```bash
   pip install -r requirements.txt
```
## Running the Application
Run the Streamlit app with:
```bash
streamlit run app.py
```
Open your browser and navigate to http://localhost:8501 to use the application.

## Directory Structure
```code
.
├── app.py
├── pathway.py
├── languages.py
├── requirements.txt
└── README.md
```
## File Descriptions
app.py: The main Streamlit application file.

pathway.py: Custom module for additional text processing.

languages.py: Contains a list of supported languages for translation.

requirements.txt: Lists the Python dependencies.

## Example Usage
1.Enter the text you want to translate in the text area.

2.Select the target language from the dropdown menu.

3.Click the 'Translate' button to see the translated and processed text.

## Requirements
The requirements.txt file includes:
```bash
streamlit
googletrans==4.0.0-rc1
```

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
Streamlit: For providing an easy way to build interactive web apps with Python.

Googletrans: For offering a simple interface to Google's translation services.

Pathway Module: Custom module developed to demonstrate additional text processing.



