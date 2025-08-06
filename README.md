# AI-Plan-Generator
This is an interactive Python script that leverages the power of AI to create personalized workout and meal plans. By collecting your specific health metrics and fitness goals, the program uses the **LangChain** framework to generate a detailed, day-by-day plan tailored just for you. It's a simple yet powerful tool for anyone looking to get a customized fitness or nutrition plan without a complex application.

-----

### Key Features

  * **Interactive Input:** The script prompts the user to enter detailed personal information, including age, gender, weight, height, and specific goals.
  * **AI-Powered Plans:** Utilizes a large language model (via LangChain) to generate intelligent and context-aware plans.
  * **Pydantic Data Model:** A robust data model ensures all user input is validated and structured correctly for consistent performance.
  * **Customizable Goals & Tasks:** Supports various fitness goals (e.g., "build muscle," "lose weight") and can generate different plan types (e.g., "meal planning," "workout plan").
  * **Detailed Output:** Provides a comprehensive weekly plan broken down by day, making it easy to follow.

-----

### Getting Started

To run this project, you'll need Python installed on your system and an **OpenAI API key**.

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/parisa-kavian/AI-Plan-Generator.git
   
    ```

2.  **Install the dependencies:**

    ```bash
    pip install langchain openai pydantic
    ```

3.  **Set your OpenAI API Key:**
    The script requires your API key to access the language model. You can set it as an environment variable or add it directly to the code where the `ChatOpenAI` model is initialized.

4.  **Run the script:**

    ```bash
    python Main.py
    ```

The program will then guide you through a series of questions to generate your personalized plan.
