# Meeting Preparation Crew AI

## Introduction
This project aims to automate meeting preparation tasks using artificial intelligence. It streamlines processes such as research, analysis, and strategy development, providing a comprehensive solution for efficient meeting planning.

## Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/gapilongo/crewai/
    cd meeting-preparation-crew-ai
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up environment variables:**
    - `OPENAI_API_KEY`: OpenAI API key for language processing.
    - `LANGCHAIN_API_KEY`: Langchain API key for language processing.
    - `LANGCHAIN_TRACING_V2`: Langchain tracing v2 endpoint.
    - `LANGCHAIN_ENDPOINT`: Langchain endpoint.

## Usage
1. **Run the main script:**
    ```bash
    python main.py
    ```

2. **Follow the prompts:**
    - Provide meeting participants' emails.
    - Specify the meeting context.
    - Define the meeting objectives.

3. **View the results:**
    The application will execute tasks and generate results for research, analysis, strategy development, and briefing compilation.

## Structure
- `main.py`: Main entry point of the application.
- `agents.py`: Defines agents responsible for different tasks.
- `tasks.py`: Defines tasks to be executed by agents.
- `tools.py`: Contains tools for web search and content retrieval.
- `crewai/`: Directory containing the CrewAI framework.

## Contributing
Contributions to improve the Meeting Preparation Crew AI are welcome! Follow these guidelines:
- Fork the repository.
- Create a new branch (`git checkout -b feature/improvement`).
- Make changes.
- Commit changes (`git commit -am 'Add new feature'`).
- Push to the branch (`git push origin feature/improvement`).
- Create a new Pull Request.

## Acknowledgements
- Utilizes the CrewAI framework.
- Thanks to OpenAI for language processing capabilities.
