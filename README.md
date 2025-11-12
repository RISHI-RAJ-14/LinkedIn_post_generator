# AI-Powered LinkedIn Content Generator

A generative AI application that analyzes LinkedIn influencers' posting patterns and creates new content matching their unique writing style.

## 🚀 Live Demo

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://linkedinpostgenerator-9pvdmrsbgx3djwffncaybr.streamlit.app/)


# Overview
This tool helps content creators and LinkedIn influencers maintain consistent engagement by generating new posts that align with their established voice and style. By analyzing historical content, the AI learns writing patterns and produces relevant, style-matched posts for future publication.

# How It Works
## Use Case Scenario
Mohan, a LinkedIn influencer, wants to maintain his posting consistency but needs assistance with content creation. By providing his previous posts to this tool, he can:

- Extract key topics and themes from his content

- Generate new posts that mirror his unique writing style

- Customize post length, language, and focus areas

## System Architecture
![App Architecture](resources/architecture.jpg)

The application operates in two main stages:

### Stage 1: Content Analysis

- Processes historical LinkedIn posts

- Extracts metadata including topics, language preferences, and content length

- Identifies writing patterns and style characteristics

### Stage 2: Content Generation

- Uses extracted parameters to create new posts

- Implements few-shot learning with relevant historical examples

- Maintains consistent writing style across generated content

- Supports customization of topic, language, and length parameters

# Installation and Setup
## Prerequisites
- Python 3.8 or higher

- Groq Cloud API access

## Configuration Steps
### 1 Obtain API Credentials

- Visit Groq Cloud Console

- Generate your API key

- Create a .env file in the project root

- Add your key: ``` bash GROQ_API_KEY=your_actual_key_here ```

### 2 Install Dependencies

```bash
pip install -r requirements.txt
```
### 3 Launch Application

```bash
streamlit run main.py
```
# Technical Implementation
## Core Technologies
- Large Language Models: Llama 3.2 via Groq Cloud

- AI Framework: LangChain for orchestration

- Web Interface: Streamlit for interactive UI

- Data Processing: Pandas for metadata management

- Programming Language: Python

## Key Features
- Real-time content generation with low latency

- Support for multiple languages including English and Hinglish

- Customizable content parameters

- Style-consistent post generation

- Interactive user interface

# License
This project is licensed under the MIT License. Commercial usage requires explicit written permission from the author. Proper attribution must be included in all derivative works or substantial portions of the software.

---

**Copyright Notice**: This software is developed and maintained by Codebasics Inc. All rights reserved for commercial applications.
