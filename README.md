# Speech Synthesis with 🤗 Transformers

## Overview

The **Speech Synthesis with 🤗 Transformers** project is a versatile Python tool that empowers users to convert text into natural-sounding speech. This project leverages state-of-the-art models from the **🤗 Transformers** library, enabling text-to-speech synthesis with various voices and styles. Whether you're building accessibility tools, voice assistants, or exploring creative applications, this project offers endless possibilities in speech synthesis.

## Features

- **Text-to-Speech Conversion:** Convert plain text into high-quality speech using cutting-edge models.
- **Voice Variety:** Synthesize speech with different voices by specifying the desired speaker.
- **Efficient Audio Generation:** Automatically generate unique audio files for each conversion.
- **Dynamic Speaker Embeddings:** Utilize speaker embeddings to mimic the characteristics of specific speakers.
- **GPU Acceleration:** Leverage GPU acceleration for faster processing (if available).

## Getting Started

### Prerequisites

Before using this project, ensure you have the following dependencies installed:

- **transformers** library
- **datasets** library
- **soundfile** library
- **torch** library
- **random** and **string** libraries
- **torch.cuda** (optional, for GPU acceleration)

You can install these dependencies using the following command:
$ pip install transformers[torch] datasets soundfile

### Usage
1. Clone the Project Repository:
`git clone https://github.com/shivanisehrawat4/Speech-Synthesis-with-Transformers.git`
`cd speech-synthesis-with-transformers`

2. Open the Jupyter Notebook:
`jupyter notebook speech_synthesis.ipynb`

3. Follow the Notebook Instructions:
- Execute each cell in the Jupyter Notebook sequentially.
- Input the desired text for speech synthesis.
- Optionally, specify a speaker to customize the voice (see available speakers in the notebook).
- Run the notebook cells to generate and play the synthesized speech.

4. Enjoy the Synthesized Speech:
Listen to the synthesized speech directly from the notebook or save it as an audio file.

### Documentation
For detailed documentation on how to use this project, please refer to the Jupyter Notebook provided with the project.

### Acknowledgments
🤗 Transformers library for providing cutting-edge text-to-speech models.
