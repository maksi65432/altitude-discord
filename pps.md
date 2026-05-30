# Privacy Policy for Altitude

Last Updated: 30/05/2026

We respect your privacy and are committed to protecting the data of our users. This Privacy Policy explains how Altitude ("Bot") collects, uses, processes, and stores data when you interact with it on Discord.

By adding the Bot to your server or interacting with it, you agree to the collection and use of information in accordance with this policy.

---

### 1. Information We Collect
To function properly, the Bot collects and processes limited data from Discord:
*   **User IDs, Channel IDs, and Guild (Server) IDs:** Used to route messages and recognize active chat contexts.
*   **Message Content:** The Bot utilizes the Discord "Message Content Intent." It only reads and processes message content under the following conditions:
    *   In Direct Messages (DMs) with the Bot.
    *   In the designated active channel when the message contains a monitored trigger word, directly mentions (pings) the Bot, or replies to a message sent by the Bot.
*   **Temporary Conversational History:** The Bot temporarily retains a short conversational context window (up to 15 messages) in its active memory to provide coherent conversational replies.

### 2. How We Use the Information
The collected information is used solely to:
*   Route conversational AI responses to the correct channel or Direct Message.
*   Provide context-aware AI interactions.
*   Execute routing commands (such as switching active channels or DMs) requested during conversations.

### 3. Data Sharing and Third-Party API Processing
The Bot does not sell, rent, or distribute your data to third parties. However, to generate conversational responses, message content is transmitted to third-party artificial intelligence engines:
*   **Mistral AI API:** Messages may be sent to Mistral AI's processing endpoints. This data is subject to [Mistral AI's Privacy Policy](https://mistral.ai/privacy-policy/).
*   **Local LLaMA Server:** Some data may be processed on a privately hosted, local LLaMA instance. This data does not leave our private infrastructure.

### 4. Data Retention and Storage
*   We do not use a persistent database (like SQL or MongoDB) to store your chat history or personal data.
*   All conversation logs are stored temporarily in the Bot's active RAM (in-memory).
*   These temporary logs are automatically cleared when the context window limit is exceeded or when the Bot is restarted.

### 5. Your Rights and Data Deletion
Since we do not permanently store your data on disk, there is no permanent archive of your messages to delete. However, you can stop the Bot from processing your data at any time by:
*   Removing (kicking) the Bot from your server.
*   Stopping interactions with the Bot in Direct Messages.
*   If you have specific data concerns, you may contact the operator at `@juniortonystark`.

### 6. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. We will notify users of any changes by updating the "Last Updated" date at the top of this document.
