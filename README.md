#AI Mental Well-Being Assistant

An AI-driven application to support mental health, providing journaling, sentiment analysis, relaxation exercises, and personalized feedback to help manage emotional well-being.

##Features

###Journaling: Safely write and store emotional entries with sentiment analysis and AI reflections.

###Relaxation Tools: Guided breathing and mindfulness exercises.

###Personalized Recommendations: Daily well-being tips and suggestions.

###Safety Panel: Emergency resources and grounding techniques.

##Installation

Install Python 3.10+: Download Python

Set up a Virtual Environment:

python -m venv venv
venv\Scripts\activate (Windows) or source venv/bin/activate (macOS/Linux)


##Install Dependencies:

pip install -r requirements.txt


Set OpenAI API Key: Create a .env file and add:

OPENAI_API_KEY=your_api_key_here


##Run the Application:

streamlit run app.py


Open the app at http://localhost:8501 in your browser.

##Project Structure
/app.py             - Main app
/agents.py          - AI agents for emotional support
/sentiment.py       - Sentiment analysis
/storage.py         - Local storage (JSON)
/tools_ui.py        - UI modules
/data/journal.json  - Journal entries

##Technologies Used

Python 3.10+

Streamlit for UI

OpenAI API for AI-driven responses

TextBlob for sentiment analysis
