# Ai-Chatbot-Streamlit
Chatbot with GROQ, llama3-8b-8192, streamlit and Python

# Llama3-Groq-Streamlit Chat Application
This project showcases a chat application built with Streamlit that integrates Llama3 models via the Groq platform. It's designed to offer speedy real-time AI-driven chat functionalities, making the most of Llama3's capabilities within an interactive web interface.

https://github.com/Op27/llama3-groq-streamlit/assets/39921621/288d5390-9c7e-4840-b898-3579bcf58c4a

## Features
- **Llama3 Integration**: Leverages the Llama3 and other major models, such as Mixtral and Gemma, to provide intelligent and context-aware responses.
- **Groq Platform**: Utilizes Groq's powerful computation capabilities to ensure fast and efficient model responses.
- **Streamlit Interface**: Offers a user-friendly web interface that allows users to interact with the AI dynamically.
- **Real-Time Responses**: Engineered to handle user inputs and deliver AI responses in real time.

## Technologies Used
- Python 3.x
- Streamlit
- Groq API
- dotenv for environment management

## Getting Started

### Prerequisites
Ensure you have Python 3.6 or higher installed on your system. Streamlit and other required packages will be installed via the requirements file.

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Op27/llama3-groq-streamlit.git
    ```
2. Navigate to the project directory:
    ```bash
    cd llama3-groq-streamlit
    ```
3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Configuration
### Obtaining a Groq API Key
To use this application, you'll need an API key from Groq. Visit the [Groq API documentation](https://console.groq.com/docs/quickstart) to learn how to obtain one.

### Setting Up Your Environment
Once you have your API key, you need to set it in your environment:
- Rename `.env.example` to `.env`.
- Open the `.env` file and replace `YOUR_API_KEY_HERE` with your Groq API key.

This step is crucial for the application to interact with Groq's services securely.

## Running the Application
To run the application, use the following command:
    ```bash
    streamlit run main.py
    ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

PERSONEL NOTE:
1. On the terminal section run this code: export GROQ_API_KEY=apikeycreated from groq cloud
2. to run after step 1 type streamlit run main.py

YT CHANNELS:
https://www.youtube.com/watch?v=bl_iSu7zW-k
https://youtu.be/02cdCd43Ccc?si=dqtKcl5WVP2WRzWl
https://youtu.be/ySwJT3Z1MFI?si=D7aGz22DIGCU4wqz
