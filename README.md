# Groq-Whisper-Transcription-App


![image_alt](https://github.com/Bhaveshwagh04/Groq-Whisper-Transcription-App/blob/main/transcription.png?raw=true)


## How to run:

1. create an environment

```bash
conda create -n transcription python==3.10 -y
```
2. Activate the environment

```bash
conda activate transcription
```
3. install requirements
```bash
pip install -r requirements
```
# Create a .env file in the root directory and add your GROQ_API_KEY credentials as follows:

GROQ_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"

# Finally run the following command
streamlit run app.py