
# Interview Prep Helper

This project leverages the power of `ollama` , `llama2` and `crewai` to provide a cutting-edge AI model experience, running entirely locally and free of charge. It's designed to automatically adapt to your system's capabilities, selecting the most appropriate model size up to 70b, depending on your hardware specifications.

## Features

- **Local Execution**: Runs on your local machine without the need for cloud processing, ensuring privacy and reducing latency.
- **Free Usage**: Utilize the `llama2` model without incurring cloud computing costs.
- **Flexible Model Support**: Supports models up to 70b, with `ollama` intelligently selecting the best model based on your system's hardware.

## Prerequisites

Before you get started, ensure you have the following installed on your system:
- `ollama` CLI tool
- Adequate hardware to support model sizes up to 70b (optional, as `ollama` will adjust based on your system's capabilities)

## Installation

1. Clone this repository to your local machine:
   ```
   [git clone <Ollama-crewai-interview-prep>](https://github.com/Rangasatyaviswapavan/Ollama-crewai-interview-prep.git)
   ```
2. Navigate into the project directory:
   ```
   cd <Ollama-crewai-interview-prep>
   ```

## Running the Project

To run the project locally with the `llama2` model:

1. Set the model name and custom model name in the script

2. Execute the script to prepare your environment.

## Customizing the Model

The project uses the 7b model by default, ensuring compatibility with a wide range of systems. If your hardware supports larger models, `ollama` will automatically detect this and can utilize up to a 70b model for enhanced performance.

## Contributing

We welcome contributions! Please feel free to submit pull requests or create issues for bugs and feature requests.

