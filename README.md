🧠 Multi-Agent AI System for Financial Transaction Monitoring

  📄 Project Description

    This notebook implements a modular, multilingual AI system for analyzing financial transaction messages.
    It uses a multi-agent architecture, where each agent handles a specific function — from natural language
    translation to fraud detection and database storage.

  🔧 Key Features
    
    ✅ Multi-Agent Design
    Each component is an autonomous agent:

    🗣️ LanguageAgent
    Translates user input from any language into English using Google Translate.

    🔍 ParsingAgent
    Extracts the amount, currency, and recipient from free-form messages.

    🛡️ FraudDetectionAgent
    Applies a trained ML model to flag potentially suspicious transactions.

    🗄️ DatabaseAgent
    Stores all transactions into a real-time SQLite database for audit and analysis.

    📢 ReportingAgent
    Generates a natural-language report summarizing the transaction and its risk status.

🌐 Language Support

    Accepts messages in any language (e.g., English, Persian).
    Translates input to English for uniform processing.
    Stores the original message and translated version in the database.

🧪 Example Use Cases

    "Transfer 5000 dollars to Jack" → ✅ Safe Transaction
    "ارسال ۸۰۰۰ تومان به علی" → ✅ Processed via translation
    "Send 9000 to Unknown" → ❗ Flagged as suspicious

🧰 Technologies Used

    Python 3
    Gradio for interactive interface
    Google Translate API
    SQLite for persistent storage
    Scikit-learn for fraud detection
    Pandas for data processing

🧠 Designed For:

    Financial AI research
    Fraud detection proof-of-concepts
    Chatbot and agent-based systems
    Educational or prototype banking apps
