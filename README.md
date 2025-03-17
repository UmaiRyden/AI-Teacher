# AI Teacher Project

## Overview
The **AI Teacher Project** is an intelligent tutoring system designed to enhance personalized learning experiences. Using **LLMs and LangChain**, this project can dynamically respond to student queries, generate explanations, and assist with subject-specific problems.

## Features
- AI-powered responses to student questions.
- Interactive learning experiences using **LangChain**.
- Customizable subject-based assistance.
- Scalable for different education levels.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/AI_Teacher.git
   cd AI_Teacher
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Setup
1. **Configure API Keys (If Required):**
   - Store API keys in a `.env` file and add it to `.gitignore`.
   - Example `.env` file:
     ```env
     OPENAI_API_KEY=your_api_key_here
     ```
   - Load these keys securely in your script using `dotenv`:
     ```python
     from dotenv import load_dotenv
     import os

     load_dotenv()
     OPENAI_API_KEY = os.getenv("OPENAI_API_KEY")
     ```

## Usage
1. Run the Jupyter Notebook:
   ```sh
   jupyter notebook AI_Teacher.ipynb
   ```
2. Follow the notebook instructions to interact with the AI tutor.
3. Customize the subject areas and responses as needed.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss proposed modifications.

## License
This project is licensed under the MIT License.

## Contact
For any questions, reach out via GitHub Issues.
