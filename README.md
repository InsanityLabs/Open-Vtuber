# Open-Vtuber

An open-source AI VTuber project that creates an interactive virtual character powered by advanced language models and real-time animation.

## Overview

Open-Vtuber is an ambitious project aimed at creating a sophisticated AI-powered virtual character, similar in concept to Neuro-sama but with unique capabilities. The system combines large language models, emotion recognition, and real-time animation to create an engaging and responsive virtual presence.

## Architecture

### Language Model Backend
- **LM Studio**: Used as the primary LLM API interface
- **DeepSeek R1 7B**: Core language model for generating responses
- **SesameAILabs CSM**: Complementary model for enhanced capabilities

### VTuber Animation System
- **Custom VTS Driver**: Proprietary driver that maintains a persistent connection to the model
- **Real-time Animation**: Precise lip synchronization and facial movements
- **Emotion Tags**: Support for emotional expressions through tags like `<happy>`, `<sad>`, `<scared>`, etc.

### Memory Management
- **Local Mem0**: Open-source memory system for context retention
- **Custom Filter System**: Advanced filtering for appropriate content and responses

### Additional Components
- **MCP Server**: Management and control protocol server for system coordination

## Future Development

- **Custom LLM**: Development of a purpose-built language model specifically for VTuber applications
- **Enhanced Animation**: More sophisticated movement and expression capabilities
- **Expanded Emotion Range**: Additional emotional states and expressions
- **Improved Context Handling**: Better memory and context management for more coherent interactions

## Getting Started

*Detailed setup and installation instructions will be added as the project develops.*

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the Apache License 2.0 - see the LICENSE file for details.
