# Multimodal AI Assistant with Image and Voice Interaction
 <br>
 Author - Aayush Kunwar
 <br>
This project provides an AI-powered assistant that can process both voice and image inputs. The assistant transcribes spoken input to text, analyzes the content of an image, and generates detailed descriptions. It then converts the AI-generated response back to speech, allowing for a seamless interactive experience.

## Features
- **Voice Input**: Speak into the microphone, and the assistant will transcribe your speech to text.
- **Image Analysis**: Upload an image, and the assistant will generate a detailed description.
- **Voice Output**: The assistant's response is converted back to audio, allowing you to hear the generated description.
- **User Interface**: A simple and intuitive web interface for easy interaction.

## Installation

To install the required dependencies, run the following commands:

```sh
pip install transformers==4.37.2
pip install bitsandbytes==0.41.3 accelerate==0.25.0
pip install git+https://github.com/openai/whisper.git
pip install gradio
pip install gTTS
