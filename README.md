# Image Generator App using STABLE DIFFUSION(Stable Bud)
Stable Bud is a simple GUI application that uses the Hugging Face model, CompVis/stable-diffusion-v1-4, to generate images based on a given prompt. The app is built using tkinter and customtkinter for a sleeker appearance.Stable Diffusion is a generative modeling technique that is based on the concept of diffusing noise through a series of steps to gradually create an image. It is a part of the family of generative models used for image synthesis, similar to other techniques like Generative Adversarial Networks (GANs) and Variational Autoencoders (VAEs).
## Installation & Setup
### Prerequisites
- Python 3.10
- pip
### Dependencies
Use the following command to install all necessary dependencies:
```python
pip install tkinter customtkinter Pillow numpy torch transformers diffusers
```
Note: Ensure that you have installed the right versions compatible with your Python environment.

### API Token
This app uses a Hugging Face model which requires an authentication token. Store your authentication token inside authtoken.py as follows:
```python
auth_token = "YOUR_HUGGINGFACE_API_TOKEN_HERE"

```
Replace **YOUR_HUGGINGFACE_API_TOKEN_HERE** with your actual token.

### Usage
Run the app.py (or the filename you have saved the code in) to launch the GUI:

```python
python app.py
```
1. Input your desired prompt in the provided text box.
2. Click the "Generate" button.
3. The generated image will be displayed in the application and saved as **generatedimage.png** in the application's directory.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.



