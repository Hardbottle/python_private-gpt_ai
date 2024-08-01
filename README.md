# Python_private-gpt_ai

Install Python 3.11 

        ****if you have multiple python version****
        - add "py -3.11 -m" before every command


Install poetry:

        - pip install poetry

PrivateGPT Setup:
        
        - poetry install --extras "ui embeddings-huggingface llms-llama-cpp vector-stores-qdrant"

        - For more info on intaller check : https://docs.privategpt.dev/installation/getting-started/installation

        Run setup
        - poetry run python scripts/setup

        ****LLM model maybe lock by huggingface_token****
        - pip install --upgrade huggingface_hub
        - huggingface-cli login ****don't add "py -3.11 -m" before****
        - YOUR_ACCESS_TOKEN

To run PrivateGPT

        - poetry run python -m private_gpt


Install dependency for main.py

        - pip install pgpt_python
        - pip install SpeechRecognition
        - pip install pyaudio
        - pip install setuptools
        - pip install gTTS
        - pip install pygame 
        - pip install pypdf
        - pip install langchain_community

To run main script

        - main.py
