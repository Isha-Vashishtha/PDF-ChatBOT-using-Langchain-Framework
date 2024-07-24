## PDF-ChatBOT-using-Langchain-Framework

#  Overview
The purpose of this project is to produce a chatbot that can engage with a wide variety of PDFs uploaded to it through the use of Gemini Pro, for instance. The bot is able to understand and address different user queries alongside generating summaries and responses in case of questions.

# Features
1.Upload and interact with numerous PDFs.
2.Natural language processing using Gemini Pro API.
3.Give correct feedback to users’ inquiries.
4.Document summaries provision.
5.Has a friendly user interface for the front-end side.

# # Installation Requirements
1.Python 3.8+
2.pip package manager
3.Gemini Pro API key

#  Screenshots
![pdf chatbot1](https://github.com/user-attachments/assets/466cc553-3a06-4ff6-a35f-93a254427efe)
![pdf chatbot2](https://github.com/user-attachments/assets/7583f95d-c90f-4367-8618-0e1fb851946b)
![pdf chatbot3](https://github.com/user-attachments/assets/e221a7ee-02a5-4931-888a-97b3df5e4488)

# Installation Prerequisites
1.Python 3.8+
2.pip package manager
3.Gemini Pro API key

# Libraries and Dependencies
1.Install the required libraries using pip:
pip install streamlit requests PyPDF2

2.Set Up Gemini Pro API Key
3.Obtain your Gemini Pro API key.
4.Create a .env file in the project root directory and add your API key:
GEMINI_API_KEY=your_gemini_pro_api_key

# Usage
Running the Chatbot
1.Clone this repository:
 git clone https://github.com/yourusername/qna-chatbot.git
cd qna-chatbot

2.Ensure you have your .env file set up with your Gemini Pro API key.
3.Run the Streamlit application:
   streamlit run app.py
4.Open the provided local URL in your web browser to interact with the chatbot.

# Frontend Interface
1.Upload PDFs: Use the upload button to add multiple PDF files.
2.Ask Questions: Input your questions in the text box and submit them.
3.View Responses: Responses and summaries will be displayed in the chat area.

# Code Structure
1.app.py: Main application file containing the Streamlit frontend and backend logic.
2.requirements.txt: List of required Python libraries.
3. .env: Environment file containing the Gemini Pro API key.





