# Personal Assistant Project

<img 
     src="https://drive.google.com/uc?export=view&id=1bTDGq_vnjhXW6cT7ywWKroC_tOslXfc2" 
     alt="sample image"
     style="display: block; margin-right: auto; margin-left: auto; width: 60%;
     box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19)"/>

<img 
     src="https://drive.google.com/uc?export=view&id=1se-40oOH0om9AYTHRafGSHC4PsMSYtbe" 
     alt="sample image"
     style="display: block; margin-right: auto; margin-left: auto; width: 60%;
     box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19)"/>     

## Overview

The Personal Assistant Project is a workflow automation tool designed to streamline communication and task management. It leverages the power of OpenAI's API to process messages and deliver intelligent, automated responses within a communication channel. With its modular and scalable design, this assistant can be adapted for various use cases.

## Features

- **Real-Time Message Handling**: Automatically listens to incoming messages on a specific channel.
- **AI-Powered Responses**: Processes messages through OpenAI Assistant API to generate intelligent replies.
- **Thread Management**: Creates threads for seamless message processing.
- **Multi-Response Support**: Handles multiple responses from the AI, processing and sending them iteratively.
- **Customizable Variables**: Predefined variables simplify customization and usage.
- **Scalable Design**: Easily adaptable to other communication workflows or platforms.

## Workflow

Here’s a high-level breakdown of how the assistant works:

1. **Superchat Listener**: Monitors incoming messages on the designated communication channel.
2. **Thread Creation**: Initializes a new thread and forwards the message to OpenAI Assistant API.
3. **Variable Setup**: Defines key variables to enhance usability and modularity.
4. **AI Response Handling**: Waits for the AI to respond and processes the response data.
5. **Array Creation**: If the response includes multiple messages, organizes them into an array.
6. **Iteration**: Loops through the array to handle and send each message individually.
7. **Response Delivery**: Sends the processed responses back to the communication channel.

Refer to the **blueprint** for the project for a visual representation of the workflow.

## Getting Started

### Prerequisites

- Access to OpenAI API.
- A communication platform supporting automation (e.g., Superchat).
- Basic knowledge of Python and workflow automation.

### BluePrint

1. Download the Repository

2. Import bluprint_make.json inside your make.com scenario

### Usage

1. Set up a listener on your communication channel.
2. Test the workflow by sending a message.
3. View the automated responses generated by the assistant.

## Project Blueprint

The **blueprint** for this project visually illustrates the entire workflow, including the key steps and integrations. You can find it in the project repository under the `blueprint/` directory or refer to the visual provided above.

## Future Plans

- Integration with additional platforms (e.g., Slack, Discord).
- Advanced AI response customization.
- Support for multiple communication channels simultaneously.

## Contributing

Contributions are welcome! Feel free to submit issues, feature requests, or pull requests to enhance this project.

## License

This project is licensed under the [MIT License](LICENSE).


