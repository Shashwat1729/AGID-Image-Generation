# Image Generation

Automate high-quality image creation using AI-powered tools like Midjourney, Copilot, and Gemini. This project integrates these models for streamlined and efficient image generation, utilizing custom prompts and automation scripts.

## Features

- **Supports Multiple AI Models**: Gemini, Midjourney, and Copilot.
- **Automated Image Generation**: Automate interactions using Selenium for tools like Discord's Midjourney bot.
- **Custom Prompts**: Define your own prompts for tailored image outputs.
- **Simulated Human Interaction**: Uses randomized delays and movements to mimic human actions, preventing detection.

## Requirements

- Python 3.x
- Libraries: `selenium`, `chromedriver-autoinstaller`, `webdriver-manager`, `undetected-chromedriver`, `scikit-image`, `pyautogui`, `user_agent`

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Shashwat1729/AGID-Image-Generation.git
    cd AGID-Image-Generation
    ```
2. Install the required Python packages:
    ```bash
    pip install selenium chromedriver-autoinstaller webdriver-manager undetected-chromedriver scikit-image user_agent pyautogui
    ```
3. Install system dependencies:
    ```bash
    sudo apt-get update
    sudo apt-get install -y chromium-browser chromium-chromedriver
    ```

## Usage

1. **Prepare the Environment**:
   - Ensure `chromedriver` is installed and accessible.
   - Customize prompts in `prompts.txt`.

2. **Run Image Generation**:
   - Choose the desired model script (`Gemini.ipynb`, `Midjourney.ipynb`, `Copilot.ipynb`).
   - Execute the Jupyter Notebook to start image generation.

3. **Fast Hours Automation (Midjourney)**:
   - Use `Fast_hours_midjourney.ipynb` to automate actions on Midjourney for obtaining fast hours.

## How It Works

- **Prompts**: Reads prompts from `prompts.txt`.
- **Automation**: Uses Selenium to interact with Discord, sending prompts and downloading generated images.
- **File Management**: Organizes output in structured directories, manages duplicates, and handles missing files gracefully.

## File Structure

- `Gemini.ipynb`: Image generation using Gemini.
- `Midjourney.ipynb`: Image generation using Midjourney.
- `Copilot.ipynb`: Image generation using Copilot.
- `Fast_hours_midjourney.ipynb`: Automates activity on Midjourney for fast hours.
- `prompts.txt`: Text file with prompts for image generation.

## Contribution

Contributions are welcome! Feel free to fork this project and submit pull requests.

## License

This project is licensed under the MIT License.

