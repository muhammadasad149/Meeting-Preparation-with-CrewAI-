# Meeting Preparation Assistant

This is a Python-based project that assists in meeting preparation by automating tasks such as research, industry analysis, meeting strategy development, and summary and briefing generation. It utilizes the CrewAI library for task delegation and execution, and integrates with Google's Generative AI for natural language processing tasks.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your local machine.
- Access to Google's Generative AI service.
- A Google API key, which you can obtain [here](https://aistudio.google.com/app/apikey).
- a EXA_API_KEY , which you can obtain [here](https://exa.ai/)

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/meeting-preparation-assistant.git
   ```

2. Navigate to the project directory:

   ```bash
   cd meeting-preparation-assistant
   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

## Configuration

1. Create a `.env` file in the project directory.

2. Add your Google API key to the `.env` file:

   ```
   GOOGLE_API_KEY=your_google_api_key_here
   EXA_API_KEY = your_EXA_API_KEY 
   ```

## Usage

1. Run the `main.py` script:

   ```bash
   python main.py
   ```

2. Follow the prompts to provide information about the meeting participants, context, and objectives.

3. The script will then delegate tasks to various agents and generate meeting preparation materials accordingly.

## Contributing

Contributions are welcome! If you have any ideas, enhancements, or bug fixes, feel free to open an issue or submit a pull request.
