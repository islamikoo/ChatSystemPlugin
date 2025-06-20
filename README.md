# Chat System Plugin for Unreal Engine

> **[Insert plugin logo or main screenshot here]**

## Overview

The **Chat System Plugin** is designed to supercharge your productivity in Unreal Engine. It acts as your intelligent assistant, helping you with any task inside the Unreal Editor from answering questions and generating code to debugging issues and managing assets. By integrating advanced AI models, the plugin aims to boost your workflow, reduce repetitive work, and help you solve problems faster, so you can focus on creativity and production.

---

## Features

- AI-powered chat with support for text and images
- Context memory for more natural conversations
- Integration with OpenAI (GPT-4o, GPT-4, etc.) and Google Gemini
- Easy-to-use settings panel for API keys and model selection
- Extensible for future features (e.g., image generation)

---

## Upcoming Features

- **Image Generation:** Generate images from text prompts directly in the chat (DALL·E, etc.).
- **Support for More AI Providers:** Integration with Claude, Grok, and other leading AI models.
- **Text to Speech:** Listen to AI responses with built-in text-to-speech.
- **Project Context Awareness & Issue Debugging:** The chatbot will understand your project context and help debug issues or suggest improvements.
- **Context Summarization:** Smarter context management to reduce API usage and cost.

---

## Getting Started

### 1. Installation

1. Copy the `ChatSystemPlugin` folder into your project's `Plugins` directory.
2. Enable the plugin in the Unreal Editor via **Edit > Plugins**.
3. Restart the Unreal Editor if prompted.

> **[Insert screenshot of plugin enabled in Unreal Editor]**

### 2. Configuration

Open the **Project Settings** and navigate to the **Chat System Plugin** section. Here's what each setting means:

- **OpenAI API Key:** Your secret key for accessing OpenAI models (e.g., GPT-4o, GPT-4). Required for OpenAI-powered chat.
- **Gemini API Key:** Your Google Gemini API key. Required for Gemini-powered chat.
- **Provider:** Choose which AI provider to use for chat (OpenAI or Gemini).
- **OpenAI Model:** Select the specific OpenAI model (e.g., gpt-4o-mini) for chat.
- **Gemini Model:** Select the specific Gemini model for chat.
- **Enable Context Memory:** If enabled, the chatbot will remember previous messages for more natural conversations.
- **Context Message Count:** How many previous messages are included as context. **Warning:** Using a large value here can quickly consume your API quota. This will be improved soon with automatic context summarization.

> **[Insert screenshot of settings panel with callouts for each input]**

---

## Using the Chatbot

- Open the chatbot UI from the plugin menu or your custom integration.
- Type your message and press Enter to chat with the AI.
- To send images, use the image upload button (if enabled).
- The chat history will display both text and image messages.

> **[Insert screenshot of chat UI in action]**

---

## Tips & Troubleshooting

- **API Keys:** Make sure your API keys are valid and have sufficient quota.
- **Model Support:** Some models may not support images. Choose a model with image support for best results.
- **Settings Not Updating:** If changes to API keys or settings do not take effect, try closing and reopening the chatbot window.
- **Clearing Chat History:** To clear the chatbot history, delete the JSON file located at:
  - `<ProjectDir>/Saved/ChatHistory/_chat_history.json`
  Then, reopen the chatbot.
- **Large Context Warning:** Setting a high context message count can increase API usage and cost. Upcoming updates will add context summarization to optimize this.
- **Logs:** Check the Output Log for error messages if something isn't working as expected.

---

## Support & Feedback

For support, feature requests, or bug reports, please contact the author or use the issue tracker on the plugin's distribution page.

---

## License

This plugin is licensed for distribution on the Unreal Engine Fab Marketplace. See the source files for details.

---

> **[Add your own images and diagrams in the placeholders above to enhance the documentation!]** 