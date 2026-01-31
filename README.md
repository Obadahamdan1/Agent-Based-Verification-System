# Agent-Based Lost-and-Found System
#This Project was Done For a Hackathon so Expect Mistakes
## Overview
This project is an AI-powered simulation of a police station's lost-and-found system, specifically designed for managing lost wallets. The system utilizes **Natural Language Understanding (NLU)** to verify claims by matching a person’s Face ID and physical ID against a secure database.

## Key Features
* **Agent-Based Design:** Incorporates advanced decision-making logic to determine claim validity.
* **Deep Learning Powered:** Built with **PyTorch** for robust natural language processing and response generation.
* **Flexible Input Handling:** Utilizes **RapidFuzz** and regex for high-accuracy string matching and processing.
* **Interactive Interface:** Deployed via **Gradio**, providing a real-time, user-friendly interface in Google Colab.
* **GPU Optimized:** Fully supports CUDA acceleration for fast inference.

## Project Structure
1.  **Data Preparation:** Automated loading and preprocessing of CSV/Excel datasets.
2.  **Model Training:** Defines and optimizes the agent’s reasoning model using PyTorch.
3.  **Agent Logic:** Implementation of the reasoning layers and decision-making protocols.
4.  **Interface Deployment:** Launching the Gradio web UI for user interaction.

## Usage
### Requirements
To install the necessary dependencies, run:
`pip install openpyxl rapidfuzz torch gradio`

### Running the System
1.  Open the notebook in **Google Colab**.
2.  **Enable GPU:** Go to `Runtime` > `Change runtime type` > `GPU (T4/L4 recommended)`.
3.  **Execute:** Run all cells to initialize data, train the agent, and launch the interface.
4.  **Interact:** Follow the Gradio link provided in the final cell to start the simulation.

## Future Improvements
* **Reasoning Expansion:** Extending the agent's logic for complex multi-turn verification.
* **Multi-Agent Collaboration:** Introducing specialized agents for different lost item categories.
* **API Integration:** Connecting to external databases for real-world application.
* **Contextual Memory:** Enhancing the system's ability to remember previous interactions.

## Team Members
* **Razan Takruri**
* **Renad Naser** (Leader)
* **Obada Hamdan**
