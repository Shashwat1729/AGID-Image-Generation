
# Image Generation Projects

## Overview
This repository comprises scripts designed for image generation utilizing three distinct models: Gemini, Midjourney, and Copilot. The prompts necessary for image generation are stored in the `prompts.txt` file within the same directory.

## File Structure
- `Gemini.ipynb`: Jupyter Notebook dedicated to image generation using the Gemini model.
- `Midjourney.ipynb`: Jupyter Notebook dedicated to image generation using the Midjourney model.
- `Copilot.ipynb`: Jupyter Notebook dedicated to image generation using the Copilot model.
- `Fast_hours_midjourney.ipynb`: Jupyter Notebook dedicated to automate actions on the Midjourney website to simulate user activity to obtain fast hours.
- `prompts.txt`: Text file containing prompts essential for image generation.

# Midjourney Image Generation

This project utilizes Selenium to automate image generation on Discord using the Midjourney bot.

## Installation

1. Install the necessary packages:
   ```bash
   !pip install selenium chromedriver-autoinstaller webdriver-manager undetected-chromedriver scikit-image user_agent pyautogui
   ```

2. Update system packages:
   ```bash
   !apt-get update
   !apt-get install -y chromium-browser
   !apt-get install chromium-chromedriver
   ```

## Usage

1. Clone the repository or download the code files.
2. Make sure you have the required packages installed as per the installation instructions.
3. Run the code to generate images based on prompts provided in the `prompts.txt` file.

## Code Overview

- `main.ipynb`: Contains the main code for image generation. (main - Gemini, Copilot or Midjourney)
- `prompts.txt`: Stores the prompts for generating images, with each prompt on a new line.

## How It Works

1. Reads prompts from `prompts.txt`.
2. Uses Selenium to interact with Discord and the Midjourney bot.
3. Enters prompts into Discord, triggering image generation.
4. Downloads and processes generated images into the `Midjourney` and `FMid` folders.
5. Script incorporates random time delays and mouse movements to simulate human-like interactions. This helps in avoiding detection by automated systems and enhances the realism of the automation process.

## File Naming and Management

1. Images are named systematically as Tweet_1.jpeg, Tweet_2.jpeg, etc.
2. Duplicate images are handled by keeping only the first instance and skipping subsequent duplicates.
3. Missing images are skipped during processing to ensure smooth execution.

## Important Notes

- Ensure `chromedriver` is correctly installed and accessible in your system.
- Adjust file paths and configurations as needed for your environment.
- Make sure to have an active Discord session for the bot to work properly.



Happy image generation!
