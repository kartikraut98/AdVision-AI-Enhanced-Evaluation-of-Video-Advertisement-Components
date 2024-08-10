# AdVision-AI-Enhanced-Evaluation-of-Video-Advertisement-Components

## Project Overview
AdVision is a comprehensive AI-driven project designed to evaluate and analyze various elements of video advertisements. This project was developed as part of a business school research initiative to assess how effectively advertisements convey specific messages and engage viewers. The analysis focuses on various aspects such as calls to action, emotional impact, product mentions, and visual appeal.

## Key Features
### Frame Extraction: <br>
Utilizes Vision Transformer (ViT) image processing to extract frames from video advertisements.<br>
### Text Recognition: <br>
Employs Tesseract OCR to extract and analyze text within the video frames.<br>
### Audio Summarization: <br>
Leverages BART (facebook/bart-large-cnn) for summarizing audio transcripts to understand the advertisement’s verbal content.<br>
### Content Classification: <br>
Uses BART (facebook/bart-large-mnli) for zero-shot classification of text, categorizing content based on predefined questions.<br>
### Accuracy: <br>
The models used achieved an accuracy rate of approximately 85% in identifying and categorizing the advertisement components.<br>
### Evaluation Criteria <br>
The project focuses on answering specific questions about the video advertisements, including but not limited to:

Is there a call to action to go online or purchase?<br>
Is contact information provided?<br>
Does the ad portray a sense of urgency or offer incentives?<br>
Is the ad intended to evoke specific emotions?<br>
Does the ad feature relatable characters, humor, or visual appeal?<br>
## Models Used
Vision Transformer (ViT): For image processing and frame extraction.<br>
Tesseract OCR: For text recognition within video frames.<br>
BART (facebook/bart-large-cnn): For summarizing audio transcripts.<br>
BART (facebook/bart-large-mnli): For zero-shot classification of advertisement content.<br>
## Data Availability
The dataset used in this project includes video advertisements, processed audio, generated captions, and more. This data is proprietary and can be made available upon request to the business school.
