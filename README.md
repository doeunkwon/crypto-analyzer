# Cryptocurrency Price and News Analysis

This project allows users to fetch and analyze the price history and recent news of various cryptocurrencies. By leveraging price data and news articles, the project utilizes a Generative Language Model (Gemini 1.5 Flash) to provide insights on the correlation between price movements and news events.

## Installation

To get started with this project, follow these steps:

1. **Clone the repository** (if applicable) or download the project files.

2. **Navigate to the project directory** in your terminal or command prompt.

3. **(Optional) Create a virtual environment**:
- It's a good practice to use a virtual environment to manage dependencies. You can create one by running:

   ```bash
   python3 -m venv venv
   ```

- Activate the virtual environment:
   - On **Windows**:

   ```bash
   venv\Scripts\activate
   ```

   - On **macOS/Linux**:

   ```bash
   source venv/bin/activate
   ```

4. **Install the required packages** using pip. Run the following command:

   ```bash
   pip install -r requirements.txt
   ```

5.	**Run the Jupyter Notebook**:
- Ensure you have Jupyter installed. If not, you can install it via pip:

  ```bash
  pip install notebook
  ```
  
- Launch Jupyter Notebook with the following command:

  ```bash
  jupyter notebook

- Open the provided Jupyter Notebook file in your web browser.

## API Keys

For ease of use, API keys are hardcoded into the script. Although it is typically advised to avoid hardcoding sensitive information directly in the code, this approach is taken here to simplify initial setup and testing.

## Usage

Follow the prompts in the Jupyter Notebook to select a cryptocurrency, fetch its price data and news, and generate insightful analyses.
