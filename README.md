# Compare two images using GEMINI PRO_VISION 

## Introduction
Generate a document (in DOCX format) that compares images from two specified directories (base and target) by utilizing a GEMINI Pro-vision AI model for image analysis

## Setting Up Virtual Environment and Installation
### Virtual Environment and Installation
1. **Create Virtual Environment:**
   python3 -m venv myenv
2. **Activate Virtual Environment (for Unix or MacOS):**
    WINDOWS
    myenv\Scripts\activate
3. **Install Required Packages:**
    pip install pillow google-generativeai python-dotenv python-docx 

## Folder Setup and Image Upload:
### Create Folders:
**Create BASE_DIR and TARGET_DIR folders in your project directory.**
    bash
    mkdir BASE_DIR TARGET_DIR
**Upload Images:**
    Place your images inside the BASE_DIR and Target_DIR folder.

## Configure .env File with Gemini API:
### Get Gemini API Credentials:
Obtain your Gemini API credentials from the Gemini website.
https://makersuite.google.com/app/apikey
### Create/Configure .env File:
1. Create a .env file in your project directory.
2. Add your Gemini API credentials to the .env file.

GEMINI_API_KEY=your_gemini_api_key

Ensure to replace your_gemini_api_key and your_gemini_api_secret with your actual Gemini API credentials.
