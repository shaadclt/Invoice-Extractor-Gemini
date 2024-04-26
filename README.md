# Invoice Extractor Using Gemini 1.5

The Invoice Extractor project aims to simplify the extraction of vital information from images, specifically focusing on invoices. By harnessing the capabilities of Gemini 1.5, Google's Multimodal Large Language Model (LLM), this application provides a robust solution for parsing invoice data with accuracy and efficiency. 

## Features:
- **Streamlined Extraction**: The Invoice Extractor application, built with Python and utilizing Streamlit for the frontend interface, offers a user-friendly experience for extracting and analyzing invoice data from images.
- **Multimodal LLM Integration**: Leveraging a multimodal LLM model, users can easily upload images, extract relevant information, and visualize the results in a clear and concise manner.
Usage Instructions:

## To use the Invoice Extractor application, follow these steps:
1. **Clone the Repository**:
Clone the repository using the command
```bash
git clone https://github.com/shaadclt/Invoice-Extractor-Gemini.git
```
3. **Navigate to the Project Directory**:
Move into the project directory by running
```bash
cd Invoice-Extractor-Gemini
```
3. **Install Dependencies**:
Install the required dependencies by running
```bash
pip install -r requirements.txt.
```
4. Set up Environment Variables:
Create a file named .env in the root directory of the project. Add your Google Cloud API key to the .env file with the following variable name: **GOOGLE_API_KEY=<YOUR_API_KEY>**
5. Run the Application:
Execute the below code in your terminal to start the application.
```bash
streamlit run app.py
```
 
## License
This project is licensed under the MIT License.

## Contribution
Feel free to create issues or pull requests on this repository.
