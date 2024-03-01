# Facial Recognition Media Player

## Project Overview

This project is my first attempt at creating a project using a convolutional neural network, more specifically a Multi-Task Cascaded CNN. The network model is imported from the facenet_pytorch library and trained using files found locally on the users computer. I made this project because I wanted to explore the wide field of facial recognition and understand the efficacy of using this model for generalized facial feature detection.

## Features

- **Facial Recognition**: Utilizes state-of-the-art facial recognition technology for accurate user identification.
- **Limited Feature Detection**: While not perfect, this project aims to differentiate the users expression for identification.
- **User Management**: Supports adding and managing user profiles for personalized experiences.

### Installation

To install this project, follow these steps:

```bash
git clone https://github.com/colemasterson/rizz-bot-v1.git
cd rizz-bot-v1
pip install -r requirements.txt
```

### Getting Started
In order to build your model, you need data for the model to be trained on.

 - Make sure you have a folder in the project directory, named 'photos', and add directories within that for each user/expression.

 - Fill these folders with a sizeable amount of pictures from different angles to provide a good starting point for detection.

 - Have an mp3 file that you wish to play for specific a specific facial class. My class is called coleRizz, and the song that is played is called rizz_song.mp3. Keep this same naming convention to avoid conflicts without changing the source code.

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.9 or higher
- PyTorch
- facenet_pytorch

