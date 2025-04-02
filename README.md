# BudgetBuddy: Your Financial Health Chatbot

## Overview

BudgetBuddy is a chatbot designed to provide personalized financial advice and insights based on information from reputable Dutch sources like ING.nl and Nibud.nl. It aims to help users understand their financial situation, identify areas for improvement, and make informed decisions about their money.

This project is currently under development and is intended for educational and informational purposes only. It should not be considered a substitute for professional financial advice.

## Features (Planned)

*   **Financial Health Assessment:**  Asks users questions about their income, expenses, savings, and debt to assess their overall financial health.
*   **Personalized Recommendations:** Provides tailored recommendations based on the assessment, drawing on best practices and guidelines from ING.nl and Nibud.nl.  Examples include:
    *   Budgeting tips
    *   Debt management strategies
    *   Savings goals
    *   Insurance recommendations
*   **Information Retrieval:**  Answers user questions about specific financial topics by retrieving relevant information from ING.nl and Nibud.nl.
*   **Budgeting Tools:**  (Future Enhancement)  Potentially integrate simple budgeting tools to help users track their income and expenses.
*   **Dutch Language Support:**  Primarily designed for Dutch-speaking users, with potential for future English language support.

## Data Sources

*   **ING.nl:**  Leverages publicly available financial information, articles, and calculators from ING Netherlands.
*   **Nibud.nl:**  Utilizes the expertise and resources of the National Institute for Family Finance Information (Nibud) to provide sound financial advice.

**Important Note:**  This project will adhere to the terms of service and usage guidelines of both ING.nl and Nibud.nl.  Data will be accessed responsibly and ethically, and proper attribution will be given to the original sources.  Web scraping, if used, will be implemented with respect for the websites' robots.txt files and server load.

## Technology Stack

*   **Programming Language:** Python
*   **Chatbot Framework:**  (To be determined - options include Rasa, Dialogflow, or a custom solution)
*   **Natural Language Processing (NLP):**  (To be determined - options include spaCy, NLTK, or transformers)
*   **Data Storage:**  (To be determined - options include a simple file-based database or a more robust solution like PostgreSQL)
*   **Web Scraping (if applicable):**  Beautiful Soup, Scrapy

## Installation

1.  **Clone the repository:**

    ```bash
    git clone [repository URL]
    cd BudgetBuddy
    ```

2.  **Create a virtual environment (recommended):**

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Linux/macOS
    venv\Scripts\activate  # On Windows
    ```

3.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt  # Create this file based on your chosen libraries
    ```

4.  **Set up API keys (if required by your chosen chatbot framework):**

    *   Follow the instructions for your chosen chatbot framework to obtain and configure any necessary API keys.

## Usage

1.  **Run the chatbot:**

    ```bash
    python main.py  # Or the appropriate command to start your chatbot
    ```

2.  **Interact with the chatbot:**

    *   Follow the prompts in the console or through the chosen chatbot interface.

## Contributing

We welcome contributions to BudgetBuddy!  If you'd like to contribute, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with clear and concise messages.
4.  Submit a pull request.

## Roadmap

*   **Phase 1: Core Functionality**
    *   Implement basic financial health assessment.
    *   Integrate with ING.nl and Nibud.nl for information retrieval.
    *   Develop personalized recommendations based on assessment results.
*   **Phase 2: Enhanced Features**
    *   Implement budgeting tools.
    *   Improve NLP capabilities for more natural and accurate conversations.
    *   Add support for multiple languages.
*   **Phase 3: Deployment and Maintenance**
    *   Deploy the chatbot to a web platform or messaging service.
    *   Continuously monitor and improve the chatbot's performance and accuracy.

## Disclaimer

BudgetBuddy is intended for informational purposes only and should not be considered a substitute for professional financial advice.  The information provided by the chatbot is based on publicly available data from ING.nl and Nibud.nl, and we make no guarantees about its accuracy or completeness.  Users should consult with a qualified financial advisor before making any financial decisions.

## License

MIT License

Copyright (c) 2025 Tijl Kindt, Carlos Vaquero, Elli Karma