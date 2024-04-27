# Image Generation Projects

## Overview
This repository comprises scripts designed for image generation utilizing three distinct models: Gemini, Midjourney, and Copilot. The prompts necessary for image generation are stored in the prompts.txt file within the same directory.

## File Structure
- `Gemini.ipynb`: Jupyter Notebook dedicated to image generation using the Gemini model.
- `Midjourney.ipynb`: Jupyter Notebook dedicated to image generation using the Midjourney model.
- `Copilot.ipynb`: Jupyter Notebook dedicated to image generation using the Copilot model.
- `prompts.txt`: Text file containing prompts essential for image generation.

## Instructions
1. Ensure you have installed the requisite dependencies (Selenium, Requests, etc.).
2. Open the IPYNB file corresponding to the desired model (Gemini, Midjourney, Copilot).
3. Execute the cells within the IPYNB file to generate images based on prompts sourced from prompts.txt.

## Usage
1. Open the relevant IPYNB file.
2. Load prompts from prompts.txt using Python code.
3. Utilize Selenium or other tools demonstrated in the code to interact with the image generation platform.
4. Follow the instructions provided within the IPYNB file to generate and download images.

## Code Snippets
Below are key code snippets employed in the IPYNB files:

### Loading Prompts from prompts.txt
```python
with open('prompts.txt', 'r') as file:
    prompts = file.readlines()
```

### Sending Prompts and Downloading Images using Selenium
```python
# Sending prompts and downloading images using Selenium
for prompt_text in prompts:
    # Sending prompt to image generation platform
    # Waiting for image generation
    # Downloading the generated image
    # ...
```

## Notes
- Ensure your internet connection is active for the image generation to function.
- Review prompts.txt for available prompts and make necessary additions or edits.

Happy image generation!
