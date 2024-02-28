# Speech-to-Image-generation

## Overview

Welcome to the Whisper-Stable-Diffusion Fusion Project! This project is dedicated to merging two powerful models, Whisper and Stable Diffusion, into a unified platform. The resulting model is capable of seamlessly combining the strengths of both Whisper for audio processing and Stable Diffusion for image processing.

## Features

1. **Audio-Image Fusion:** Our model integrates Whisper for transcribing speech and Stable Diffusion for image analysis, creating a comprehensive solution for both audio and image processing.

2. **Unified Platform:** Enjoy the convenience of having both Whisper and Stable Diffusion functionalities in a single application. This unified platform simplifies the workflow for users requiring both audio and image analysis.

3. **Efficient Query Processing:** With the Whisper-Stable-Diffusion fusion, users can input queries via speech or image, and the model provides output in both text and speech formats. This versatility makes the application suitable for various use cases.

## Dependencies

- [whisper]:https://github.com/openai/whisper
- [stable-diffusion]:https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Naveenpoliasetty/Speech-to-Image-generation
   ```

2. Install the required dependencies:

   ```bash
   # Follow the installation instructions for Whisper and Stable Diffusion
   # ...
   ```

3. Set up the environment:

   ```bash
   # Create and activate a virtual environment (optional but recommended)
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

4. Install project-specific requirements:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Fusion Model:**

   ```bash
   python fusion_model.py
   ```

2. **Input Queries:**

   - Provide speech input using Whisper or image input using Stable Diffusion.
   - Enjoy the combined output in both text and speech formats.

## Configuration

Adjust the configuration parameters in the `config.yml` file to customize the behavior of the fusion model.

## Credits

- **Whisper:** https://github.com/openai/whisper
- **Stable Diffusion:** https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0

## Acknowledgments

We extend our gratitude to the developers of Whisper and Stable Diffusion for their outstanding contributions to the field.

Feel free to contribute, report issues, or suggest improvements!
