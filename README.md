# Jiayu's Independent Research Project: AI Modeling of Visual Working Memory

## Overview of this project
This project simulates a visual working memory experiment (Heuer & Schubö, 2016) to test how an AI model (OpenAI’s GPT model) performs on tasks that involve spatial attention, feature-based cues, and visual working memory.

The experiment presents the AI with a 2×2 grid of 4 colored shapes (stimuli), followed by a retrocue (a cue that directs attention to one of the previously shown stimuli).
The AI must then decide whether the retrocue refers to an object that was located in a specific grid position (“yes” or “no”).

This project aims to investigate how AI systems process and reason about visual-spatial information, and how such modeling could inform the design of AI-driven interfaces that align better with human attention and memory patterns.

Reference: Heuer, A., & Schubö, A. (2016). Feature-based and spatial attentional selection in visual working memory. Memory & cognition, 44(4), 621-632.

## How to Run

1. Mount your Google Drive:

from google.colab import drive
drive.mount('/content/drive', force_remount=True)


2. Clone or upload this repository to your Drive.

Add folders:

/CueTask/stimuli/

/CueTask/retrocue_stimuli/

/CueTask/generated_trials/


3. Run the Python file

Results and generated grids will appear under /generated_trials/run_<timestamp>/.
