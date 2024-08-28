# ChatBot-GeminiAPI
This project is a simple ChatBot application built using the Gemini API and Streamlit. The ChatBot allows users to interact with an AI-powered conversational agent, providing real-time responses to user queries. The application is designed to be user-friendly and easily customizable for various conversational AI use cases. <br/>
<br/>

## Features
* Real-Time Interaction: Engage in real-time conversations with the ChatBot.
* API Integration: Powered by the Gemini API for robust conversational capabilities.
* Streamlit Interface: A clean and interactive web interface using Streamlit.
* Environment Variables: API key is managed securely using a .env file and the dotenv library. <br/>
<br/>

## Setup and Installation
**Prerequisites**
* Python 3.7 or higher
* Streamlit
* Gemini API key <br/>

**Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chatbot-gemini-api.git
   cd chatbot-gemini-api
   ```
   
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up the .env file: <br/>
Create a .env file in the root directory of the project and add your Gemini API key:
   ```bash
   GEMINI_API_KEY=your_api_key_here
   ```

5. Run the Streamlit application:
   ```bash
   streamlit run main.py
   ```
<br/>

## Usage
Once the application is running, open the provided local URL in your web browser. You can start interacting with the ChatBot by typing your queries in the text input box. <br/>
<br/>

## Customization
You can easily customize the ChatBot’s behavior by modifying the API interaction code in main.py. Additionally, the Streamlit interface can be tailored to fit specific design requirements.

