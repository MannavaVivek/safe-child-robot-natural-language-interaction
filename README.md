# Safe Child-Robot Natural Language Interaction

This repository contains the supporting code for our paper "Exploring the Suitability of Conversational AI for Child-Robot Interaction," submitted to ROMAN'24.

## Requirements

To run this project, you need to have the following software and dependencies installed:

- **Rasa Open Source**  
  Installation instructions: [Rasa Documentation](https://rasa.com/docs/rasa/installation/installing-rasa-open-source)

- **ROS Noetic**  
  Installation instructions: [ROS Noetic on Ubuntu](https://wiki.ros.org/noetic/Installation/Ubuntu)
  - Python 3.8 or higher
  - Ubuntu 20.04

- **Python packages**
    - textstat
    - spacy
    - openai
    - langdetect

- **spaCy**  
  Model required: `en_core_web_trf`  
  Installation: 
  ```bash
  python -m spacy download en_core_web_trf

## ROS servers

 The ROS Noetic servers are available [here](https://github.com/MannavaVivek/SafeCRI-ROS.git)
