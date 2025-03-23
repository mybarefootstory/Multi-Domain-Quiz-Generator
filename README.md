# Multi Domain Quiz Generator

Welcome to the Multi Domain Quiz Generator! This application allows users to generate and take quizzes on various topics using multiple choice and fill-in-the-blank questions. The quizzes are generated using the Groq API, providing a dynamic and interactive learning experience.

## Features

- Generate multiple choice and fill-in-the-blank questions on any topic.
- Customize the difficulty level of the questions.
- Take quizzes directly in the application.
- View detailed results and scores after completing a quiz.
- Save quiz results to a CSV file for future reference.

## Technology Stack

- **Python**: The core programming language used for developing the application.
- **Streamlit**: A framework for building interactive web applications in Python.
- **Langchain**: Utilized for language model integration and prompt management.
- **Pydantic**: Used for data validation and settings management.
- **Python-dotenv**: For loading environment variables from a `.env` file.
- **Groq API**: Provides the language model for generating quiz questions.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mybarefootstory/Multi-Domain-Quiz-Generator.git
   cd Multi-Domain-Quiz-Generator
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment:**

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

4. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

5. **Set up the environment variables:**

   Create a `.env` file in the root directory and add your Groq API key:

   ```plaintext
   GROQ_API_KEY="your_groq_api_key_here"
   ```

## Usage

1. **Run the application:**

   ```bash
   streamlit run app.py
   ```

2. **Configure your quiz:**

   - Select the API (currently only Groq is supported).
   - Choose the type of questions (Multiple Choice or Fill in the Blank).
   - Enter the topic for the quiz.
   - Select the difficulty level (Easy, Medium, Hard).
   - Specify the number of questions.

3. **Generate and take the quiz:**

   - Click "Generate Quiz" to create the quiz.
   - Answer the questions presented in the quiz interface.
   - Submit the quiz to view your results.

4. **Save and download results:**

   - After viewing your results, you can save them to a CSV file.
   - Download the CSV file for your records.

## Future Scope

The Multi Domain Quiz Generator has several potential areas for future development:

- **Expanded Question Types:** Introduce additional question formats such as true/false, matching, and short answer questions to enhance the variety of quizzes.

- **Integration with Other APIs:** Incorporate other language models and APIs to provide a broader range of question generation capabilities and improve the diversity of content.

- **User Profiles and Progress Tracking:** Implement user accounts and profiles to track progress over time, allowing users to see their improvement and revisit past quizzes.

- **Adaptive Learning:** Develop an adaptive learning system that adjusts the difficulty of questions based on the user's performance, providing a personalized learning experience.

- **Multilingual Support:** Add support for multiple languages to cater to a global audience, making the tool accessible to non-English speakers.

- **Mobile Application:** Create a mobile version of the application to allow users to take quizzes on-the-go, increasing accessibility and convenience.

