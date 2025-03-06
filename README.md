# AI Flight Assistant with Custom Functions ✈️🤖

This repository contains an AI-powered Flight Assistant built using Ollama (Llama 3.2), LangChain, and Gradio. The assistant can interact naturally with users, check flight availability, book flights, and generate dummy flight tickets—all while leveraging custom function calling to execute specific tasks efficiently, on the mockup data provided.

## Features

- Conversational AI powered by Llama 3.2 for natural interactions
- Custom function calling via LangChain for structured outputs
- Real-time chatbot UI using Gradio
- Flight availability checking and booking simulation
- Automated ticket generation in text format

## Tech Stack

- **Ollama (Llama 3.2)**: Local LLM for intelligent responses
- **LangChain**: Manages function calling and structured responses
- **Gradio**: Provides a simple yet interactive chatbot UI
- **Python**: Core implementation

## How It Works

1. The assistant asks for flight details (source, destination, passenger info),provided in mock data.
2. It retrieves flight data via custom functions.
3. The user selects a flight, and the AI books the flight by calling backend functions.
4. A dummy flight ticket is generated as a text file.

This project is perfect for anyone interested in LLM-based assistants, function calling, and AI-driven booking workflows.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Required libraries (specified in `requirements.txt`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/harshayvyas/Ollama-Langchain-AI-Flight-Assistant-Custom-Functions.git
   cd Ollama-Langchain-AI-Flight-Assistant-Custom-Functions
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Open the Jupyter Notebook:
   ```bash
   Jupyter notebook
   ```

2. Navigate to and open the notebook file flight_assistant.ipynb.
3. Run the cells in the notebook to start the AI flight booking bot.
4. Follow the instructions in the notebook to interact with the bot and book flights.

## Custom Functions

This project demonstrates how to implement and call custom functions using the Ollama/Llama 3.2 model. The functions handle various tasks such as:
- Fetching flight details
- Booking flights

The implementation details can be found in the `custom_functions` directory.

## Mock Data

The project uses mock data to simulate flight information and availability. The mock data can be found in the `data` directory and includes:
- Flight schedules
- Pricing information
- Booking status

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact [harshayvyas](https://github.com/harshayvyas).

[Link to the repository](https://github.com/harshayvyas/Ollama-Langchain-AI-Flight-Assistant-Custom-Functions).
