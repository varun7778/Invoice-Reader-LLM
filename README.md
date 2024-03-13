 # MultiLanguage Invoice Extractor

## Overview

This project provides a web application that extracts information from invoices in multiple languages using Google AI's Gemini text-to-image model. Users can upload an invoice image, provide a prompt, and receive informative responses about the invoice content.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/varun7778/Invoice-Reader-LLM.git
   ```
2. Create a virtual environment:
   ```bash
   python -m venv env
   ```
3. Activate the virtual environment:
   - Windows:
     ```bash
     env\Scripts\activate
     ```
   - Linux/macOS:
     ```bash
     source env/bin/activate
     ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Set up a Google API key:
   1. Obtain a Google API key from the Google Cloud Console.
   2. Create a `.env` file in the project root directory and add your API key:
      ```
      GOOGLE_API_KEY=<your_api_key>
      ```

2. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Features

- Accepts invoice images in JPG, JPEG, and PNG formats.
- Handles multiple languages supported by Gemini.
- Prompt-based interactions for tailored responses.
- Clear and concise presentation of extracted information.

## Dependencies

- Python 3.7 or later
- Streamlit
- Pillow
- google-generativeai
- dotenv

## Working

![alt text](img/1.png)

![alt text](https://github.com/varun7778/Invoice-Reader-LLM/blob/5ad4ae8a6fe4d58d7b3fdfb90214229c52d21b9d/img/2.png)
