AI-powered chatbot for Supplier and Product Information

Overview

This project is an AI-powered chatbot designed to allow users to query a product and supplier database using natural language. The chatbot interacts with an open-source Large Language Model (LLM) and leverages the LangGraph framework for agent workflows to fetch relevant information from a MySQL/PostgreSQL database. Additionally, the chatbot summarizes the retrieved data using the LLM for an enhanced user experience.

Tech Stack

Frontend

React: A JavaScript library for building user interfaces.

Tailwind CSS: A utility-first CSS framework for styling.

Axios: A promise-based HTTP client for making API requests.

Backend

FastAPI: A modern, fast (high-performance) web framework for building APIs with Python 3.6+.

SQLAlchemy: A Python SQL toolkit and Object-Relational Mapping (ORM) library.

LangGraph: A framework for building agent workflows.

Transformers: A library from Hugging Face for state-of-the-art Natural Language Processing.

Database

PostgreSQL: A powerful, open-source object-relational database system.

Features

Natural Language Querying: Users can input queries like "Show me all products under brand X" or "Which suppliers provide laptops?".

Data Retrieval: The chatbot fetches relevant data from the database efficiently.

Data Summarization: Summarizes supplier and product data using an open-source LLM.

Graceful Error Handling: Handles missing or incorrect queries gracefully, ensuring a seamless user experience.

Security Measures

Database Encryption: Ensures sensitive data is stored securely.

User Authentication: Uses token-based authentication to secure API endpoints.

API Rate Limiting: Prevents abuse and ensures fair usage of resources.

Scalability Plans

Load Balancing: Distributes incoming traffic across multiple servers.

Database Optimization: Indexing and caching strategies to handle large datasets.

Horizontal Scaling: Adds more servers to meet growing demand.

Testing and Validation

Unit Testing: Tests individual components such as API endpoints and database queries.

Integration Testing: Validates the interaction between the frontend, backend, and database.

User Testing: Gathers feedback from real users to refine the chatbot experience.

Performance Metrics

Response Time: Measures how quickly the chatbot processes and responds to queries.

Accuracy: Evaluates the relevance and correctness of the retrieved and summarized data.

User Satisfaction: Collects user feedback to measure the overall effectiveness of the chatbot.

Potential Use Cases

E-commerce Platforms: Helps customers quickly find products and supplier information.

Supplier Management Systems: Assists businesses in managing and querying supplier databases.

Customer Support Systems: Provides automated assistance for common supplier and product-related queries.

Future Enhancements

Multi-language Support: Enables users to interact with the chatbot in various languages.

Advanced Analytics: Integrates analytics dashboards for insights into user queries and trends.

Expanded Database Support: Adds compatibility with other database systems like MongoDB or Microsoft SQL Server.


