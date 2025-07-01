# DocRoom - Medical Assistant Discord Bot

DocRoom is an intelligent medical assistant Discord bot that helps users with preliminary medical assessments by collecting symptoms and providing initial guidance. Built with Python and powered by Azure OpenAI's GPT-4, it offers a conversational interface for medical information gathering.

## Features

- **Natural Language Processing**: Understands and processes user inputs about medical symptoms
- **Personal Information Management**: Securely collects and manages user details
- **Interactive Diagnosis**: Guides users through symptom assessment with relevant questions
- **Context-Aware Conversations**: Maintains conversation history for coherent interactions
- **Secure & Private**: Data is handled with privacy in mind

## Prerequisites

- Python 3.8+
- Discord Bot Token
- Azure OpenAI API Key
- Azure OpenAI Endpoint
- Azure OpenAI Deployment Name

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/doc-room.git
   cd doc-room
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the root directory with the following variables:
   ```env
   DISCORD_TOKEN=your_discord_bot_token
   AZURE_OPENAI_API_KEY=your_azure_openai_api_key
   AZURE_OPENAI_ENDPOINT=your_azure_openai_endpoint
   AZURE_OPENAI_DEPLOYMENT_NAME=your_deployment_name
   AZURE_OPENAI_CHAT_DEPLOYMENT_NAME=your_chat_deployment_name
   ```

## Usage

1. Start the bot:
   ```bash
   python main.py
   ```

2. Invite the bot to your Discord server using the OAuth2 URL generated from the Discord Developer Portal.

3. Interact with the bot in any channel where it has permission to read messages and respond.

## Commands

- `!start` - Begin a new consultation
- `!help` - Show available commands
- `!clear` - Clear conversation history

## How It Works

1. The bot initiates a conversation to collect personal information
2. It then asks about symptoms and medical history
3. Using Azure OpenAI, it analyzes the information
4. Provides preliminary guidance based on the input

## Data Privacy

- All conversations are processed securely
- Personal data is not stored permanently
- The bot adheres to standard medical data protection guidelines

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, please open an issue in the GitHub repository.

---

*Note: This is a prototype application and not a substitute for professional medical advice. Always consult with a healthcare professional for medical concerns.*
