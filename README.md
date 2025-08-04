# AI-Powered Travel Planner Agent

## 1. Project Overview

This project is an intelligent, AI-powered Travel Planner Agent designed to revolutionize trip planning. It provides users with personalized and efficient travel assistance by leveraging real-time data to suggest destinations, build custom itineraries, and recommend transport and accommodation. The agent is powered by the IBM Granite foundation model and runs on IBM Cloud services.

**Main Features:**

* **AI-Powered Personalized Itineraries:** Generates tailored day-wise travel plans based on user preferences, budget, and constraints.
* **Real-Time Data Integration:** Incorporates live weather updates and local event information for a smarter travel experience.
* **Smart Recommendations:** Suggests cost-effective travel packages and authentic local attractions.
* **Conversational Interface:** Remembers user preferences to provide context-aware suggestions.

## 2. Installation Instructions

To set up the project locally, follow these steps:

1.  **Prerequisites:**
    * Ensure you have Python 3.8+ installed.
    * You will need an IBM Cloud account with access to the Watsonx.ai Studio.

2.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/ai-travel-planner.git](https://github.com/your-username/ai-travel-planner.git)
    cd ai-travel-planner
    ```

3.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Configuration:**
    * Create a `.env` file by copying the `.env.example` file.
    * Add your IBM Cloud API key and other necessary credentials to the `.env` file.

## 3. Usage

To run the Travel Planner Agent, execute the main application script from the command line:

```bash
python main.py
```

The agent will then prompt you for your travel details, such as destination, dates, budget, and interests. Interact with the agent through the command-line interface to build your personalized itinerary.

## 4. Contributing

Contributions are welcome! To contribute to the project, please follow these guidelines:

* **Reporting Issues:** If you find a bug or have a suggestion, please open an issue on the GitHub repository. Provide a clear description and steps to reproduce the issue.
* **Submitting Pull Requests:**
    1.  Fork the repository.
    2.  Create a new branch for your feature or bug fix (`git checkout -b feature/your-feature-name`).
    3.  Commit your changes (`git commit -m 'Add some feature'`).
    4.  Push to the branch (`git push origin feature/your-feature-name`).
    5.  Open a pull request with a clear description of your changes.

## 5. License

This project is released under the MIT License. See the [LICENSE](LICENSE) file for more details.
