# Text to Image Generation App
This Streamlit application, named "Text to Image Generation," enables you to generate images from text prompts using two different AI models: OpenAI's DALL-E and Huggingface Diffusers. You can input a text prompt, choose the desired AI model, and witness the generation of AI-based images.

## Getting Started
### Prerequisites
1. Python 3.7 or later
2. Streamlit
3. OpenAI
4. Diffusers
5. torch
### Installation
1. Clone this repository:
   1. git clone https://github.com/Fariqf/Text-to-image.git
   2. cd Text-to-image
      
2. Install the required packages:
   pip install -r requirements.txt
   
3. Set up your OpenAI API key by creating a .env file in the root directory:
  OPENAI_API_KEY=your_openai_api_key

4. Run the Streamlit app:
   streamlit run app.py

## How to Use
1. Choose between "DALL-E" and "Huggingface Diffusers" in the sidebar.
2. Enter your text prompt in the provided text input.
3. Click the "Generate Image" button.
4. The app will display the generated image based on the selected AI model

## Components
### DALL-E Image Generation
This section utilizes OpenAI's DALL-E model to generate images from text prompts.

### Huggingface Diffusers Image Generation
This section uses the Huggingface Diffusers model to generate images from text prompts.
