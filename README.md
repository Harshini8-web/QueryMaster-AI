# QueryMaster-AI
# Customer Support Assistant

This project creates an intelligent customer support agent using multi-agent systems to manage customer queries in real-time. The system efficiently categorizes queries, analyzes sentiment, and routes them to the appropriate support channels—Technical, Billing, or General. Queries with negative sentiment are automatically escalated to human agents, ensuring fast and effective resolution.

## Features

- **Query Categorization**: Classifies customer queries into Technical, Billing, or General categories.
- **Sentiment Analysis**: Determines whether customer queries are Positive, Neutral, or Negative.
- **Response Generation**: Automatically generates appropriate responses based on the query’s category and sentiment.
- **Escalation**: Queries with negative sentiment are automatically escalated to human agents for personalized assistance.
- **Flexible Workflow**: Powered by LangGraph, allowing for an extensible and customizable workflow that adapts to different customer interaction requirements.

## Method Details

- **Initialization**: Set up the environment and import necessary libraries.
- **State Definition**: Create a structure to hold query information including category, sentiment, and response.
- **Node Functions**: Implement functions for query categorization, sentiment analysis, and response generation.
- **Graph Construction**: Use StateGraph to define the workflow by adding nodes and edges that represent the support process.
- **Conditional Routing**: Implement logic to route queries to appropriate functions based on their category and sentiment.
- **Workflow Compilation**: Compile the workflow graph into an executable application.
- **Execution**: Process customer queries through the workflow and retrieve results.

## Installation Requirements

Ensure you have the following dependencies installed:

```bash
pip install langchain langchain_core langchain_groq langchain_community langgraph gradio
