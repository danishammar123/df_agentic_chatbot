
# Agenctic DataFrame Chatbot

A chatbot designed for interacting with tabular data (CSV/Excel files) in a conversational way, without the need for coding.
## Demo Video
click on video to see demo of the project
[![Watch the demo on YouTube](https://img.youtube.com/vi/CJGlYTn7_0g/0.jpg)](https://www.youtube.com/watch?v=CJGlYTn7_0g)

## Overview
Agenctic DataFrame Chatbot allows users to load CSV or Excel files and engage with their data in natural language. This chatbot leverages conversational AI and pandas functionality to make data analysis accessible to non-programmers, enabling users to perform a full range of DataFrame operations through simple chat interactions.

## Features
- **Conversational Data Analysis**: Chat with your data in natural language without any coding.
- **Data Loading**: Easily load and interact with CSV and Excel files.
- **Pandas Operations**: Perform filtering, sorting, aggregating, and other pandas operations directly through the chatbot interface.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/danishammar123/df_agentic_chatbot.git
   ```

2. **Set up a virtual environment** (recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scriptsctivate`
   ```

3. **Install the dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

   **Note**: This project requires Python 3.11.9.

## Usage

1. **Load your CSV or Excel file**:
   - Start the chatbot and upload a CSV or Excel file for analysis.

2. **Interact with your data**:
   - You can ask questions or request operations on your data in natural language, such as:
     - "Show me the top 10 rows."
     - "What’s the average value in the sales column?"
     - "Filter the data for records where `column_name` is greater than 100."

3. **Examples**:
   ```plaintext
   > Load file: data.csv
   > User: Show me the first 5 rows.
   > Bot: [Displays the first 5 rows of data.csv]
   
   > User: What's the sum of values in the sales column?
   > Bot: The sum of values in the 'sales' column is 1,250.
   ```

## Contributing

Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact / Support

For any questions or support, please open an issue in the GitHub repository.



## Important Libraries 
fastapi
uvicorn
python-multipart
pandas
openpyxl
langchain
langchain-experimental
langchain-openai
python-dotenv
pydantic
