# ThaparGPT
Welcome to ThaparGPT, a cutting-edge AI-powered platform designed to help campus freshers easily access essential information about college life. This solution leverages Llama3.1, Selenium, and ChromaDB on the backend, with a modern and interactive frontend built using React.

📚 Project Overview
The Campus Assistant provides an intuitive interface for freshmen to ask questions and get real-time, relevant responses. The system works as follows:

Data Parsing and Storage:

The backend uses Selenium to parse and extract important data from websites related to campus life (e.g., academic information, campus resources, events).
The parsed data is then embedded using Llama3.1 and stored in ChromaDB, a vector database for efficient querying.
LLM Query System:

Users can type in queries in natural language, and the system uses Llama3.1 to generate responses based on the stored data.
The responses are fetched and returned using a RESTful API, making the data accessible to the frontend.
Frontend Interface:

The frontend is developed using React, providing a user-friendly chat-like interface where students can easily ask questions and view AI-generated responses.
The design is simple yet effective, ensuring a smooth and engaging user experience.
🛠️ Technologies Used
Backend
Llama3.1: For language modeling and generating natural language embeddings.
Selenium: To scrape and parse relevant data from websites.
ChromaDB: A vector database used for efficient data storage and querying.
FastAPI: To create a REST API that connects the backend to the frontend.
Frontend
React: For building a dynamic and responsive user interface.
HTML/CSS: For styling and layout.
💻 How to Use
Ask a Question: Type your query in the input box and press "Send" or hit "Enter."
Get a Response: The AI will process your question and return a relevant answer in the chat interface.
Iterate: Ask follow-up questions or explore more topics as needed.
📝 Example Queries
"Where can I find the academic calendar?"
"What are the available dining options on campus?"
"How do I sign up for a club event?"
🌟 Features
Natural Language Understanding: The assistant interprets and responds to user queries using Llama3.1.
Real-Time Data Access: Thanks to the efficient setup with ChromaDB, responses are fast and relevant.
User-Friendly Interface: The React-based chat UI is intuitive and easy to use.
📈 Future Enhancements
Expand Data Sources: Integrate more data sources to provide a richer knowledge base.
Improve UI/UX: Add more interactive elements to enhance user engagement.
Voice Input: Enable voice-based queries for more accessibility.
🤝 Contributing
Feel free to contribute by opening issues or submitting pull requests. Your input and ideas are welcome!

