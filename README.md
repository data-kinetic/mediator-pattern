# AI-Powered Compliance Management System (Jupyter Notebook)

This Jupyter Notebook demonstrates an innovative approach to compliance management using the Mediator design pattern combined with AI-powered policy application and compliance checking.

## Overview

The notebook showcases a system that uses OpenAI's GPT model to evaluate compliance events in real-time, providing a flexible and adaptive approach to policy enforcement. It's built around the Mediator pattern, which centralizes complex communications between different compliance modules.

## Features

- AI-powered policy application and compliance checking
- Real-time event processing simulation
- Centralized control through a mediator
- Comprehensive logging for audit trails
- Visualization of compliance results and module activity

## Requirements

- Jupyter Notebook environment
- Python 3.9+
- OpenAI Python library
- Matplotlib
- python-dotenv

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/datakinetic/medidator-pattern.git
   cd ai-compliance-mediator-notebook
   ```

2. Install the required packages:
   ```
   pip install jupyter openai matplotlib python-dotenv
   ```

3. Set up your OpenAI API key:
   - Create a `.env` file in the project root
   - Add your OpenAI API key to the `.env` file:
     ```
     OPENAI_API_KEY=your_api_key_here
     ```

## Usage

1. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```

2. Open the `AI_Powered_Compliance_Management.ipynb` notebook in your browser.

3. Run the cells in order to:
   - Initialize the AI-Powered Compliance Management System
   - Generate sample compliance events
   - Run a simulation processing these events
   - Display compliance check results
   - Show visualizations of the results

## Notebook Structure

The notebook is structured as follows:

1. Import necessary libraries and set up OpenAI client
2. Define the Mediator interface and AI-powered Concrete Mediator
3. Implement the ComplianceModule class
4. Create functions for sample data generation and simulation
5. Main execution cell to run the simulation
6. Cells for analysis and visualization of results

## Customization

You can customize the system by:
- Modifying the `generate_sample_events()` function to create different types of events
- Adjusting the AI prompts in `check_compliance()` method to refine compliance criteria
- Adding new compliance modules by creating additional `ComplianceModule` instances
- Experimenting with different OpenAI models or parameters

## Contributing

Contributions to improve the notebook or extend its capabilities are welcome. Please feel free to fork the repository, make your changes, and submit a pull request.

## License

[MIT License](LICENSE)

## Disclaimer

This notebook is a demonstration and should not be used as-is for critical compliance management without proper review and adaptation to specific organizational needs and regulatory requirements.