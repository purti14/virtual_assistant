CONVERSATIONAL AI 🗣️
This repository contains the code for a conversational AI voice assistant built using the Python language. The project leverages the ElevenLabs API for real-time, lifelike voice synthesis, creating a dynamic and interactive user experience.

🚀 Features
Real-time voice conversation: Engage in natural, back-and-forth dialogue with the AI.

Customizable AI persona: The assistant's behavior and personality can be easily configured using a prompt.

Schedule-aware responses: The assistant can be provided with a user's schedule to offer relevant and helpful information.

Secure API key management: Uses a .env file to safely store and load sensitive API credentials.

Easy to extend: The modular design allows for easy integration of new features, such as additional APIs or custom voice models.

🛠️ Technologies
Python: The core programming language.

ElevenLabs API: Powers the voice synthesis and conversational intelligence.

python-dotenv: Manages environment variables for secure credential handling.

📦 Installation
To get the project up and running on your local machine, follow these steps:

1. Clone the repository
Bash

git clone https://github.com/your-username/conversational-ai.git
cd conversational-ai
2. Set up a virtual environment (recommended)
It's a best practice to use a virtual environment to avoid conflicts with other projects.

Bash

# Create the virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
3. Install the required packages
Bash

pip install -r requirements.txt
Note: If the requirements.txt file is not present, you can install the dependencies manually:
pip install elevenlabs python-dotenv

🔑 API Key Configuration
To use the ElevenLabs API, you need an API key and an Agent ID.

Get your credentials from your ElevenLabs profile.

Create a .env file in the root directory of the project (the same folder as voice_assistant.py).

Add your credentials to the file in the following format:

AGENT_ID="your_agent_id_here"
API_KEY="your_api_key_here"
Important: Never commit your .env file to version control. It's a security risk. The .gitignore file in this repository is already configured to ignore .env.

▶️ Usage
Once everything is set up, you can run the script from your terminal:

Bash

python voice_assistant.py
The script will start a conversational session, and you can begin speaking. The AI's responses will be played through your speakers, and your transcribed speech will be printed to the console.

🤝 Contributing
Contributions are welcome! If you find a bug or have an idea for a new feature, feel free to open an issue or submit a pull request.

