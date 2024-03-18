# Multimodal-AI-App-using-Llava-7B
Multimodal AI App using Llava 7B and Gradio. The speech to text part is handled by whisper.

![Screenshot_Llava_Multimodal](https://github.com/sunithalv/MultiModalVoiceAssistant/assets/28974154/db10fe57-d73d-4dfa-8581-978288178281)


The image is uploaded as an input and the query regarding the image is provided as a voice input using microphone.
The query is answered in the context of the image and a corresponding response in text/audio is provided.

## Clone this repository

```
git clone https://github.com/sunithalv/MultiModalVoiceAssistant.git
```

## Create a new python environment

```
conda create -n venv python==3.10 -y 
```

## Install all required libraries

```
pip install -r requirements.txt
```

## To run the application

```
python multimodal_rag.py 
```
