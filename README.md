# AutoDev AI

AI-powered GitHub automation for code reviews, documentation, and CI/CD optimization.

## Overview

AutoDev AI integrates with GitHub Actions and Google Cloud to streamline the software development lifecycle using AI. It analyzes pull requests, generates code review suggestions, optimizes CI/CD pipelines, and auto-generates documentation, helping developers ship faster and smarter.

## Features

- AI-driven code review comments
- Automated documentation generation from code
- CI/CD pipeline optimization recommendations
- Issue resolution suggestions based on commit history

## Built With

- [GitHub Actions](https://github.com/features/actions)  
- [Google Cloud Vertex AI](https://cloud.google.com/vertex-ai)  
- [LangChain](https://github.com/hwchase17/langchain)  
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)  
- [Flask](https://flask.palletsprojects.com/)  
- [OpenAI API](https://platform.openai.com/)

## Getting Started

### Prerequisites

- Python 3.8+  
- GitHub account  
- Google Cloud account with Vertex AI enabled  
- MongoDB Atlas account

### Installation

1. Clone the repo  
   ```bash
   git clone https://github.com/yourusername/autodev-ai.git

2. Create and activate a virtual environment
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. Install dependencies
   pip install -r requirements.txt

4. Configure your .env file with your API keys and credentials.
