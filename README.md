# Quick HR chatbot for Conversational AI Hackathon with IBM watsonx Assistant

This repository contains the code and JSON data for the Human Resources bot I developed. The bot is designed to assist employees with common HR-related queries, providing automated and efficient responses.

## Demo
[Click here to test my chatbot.](https://web-chat.global.assistant.watson.appdomain.cloud/preview.html?backgroundImageURL=https%3A%2F%2Fjp-tok.assistant.watson.cloud.ibm.com%2Fpublic%2Fimages%2Fupx-6f14a634-b459-4700-94f3-b109e0f10985%3A%3A50c76ce4-e012-4a74-9e87-0e01e8bd0d8e&integrationID=2ec0598a-67ba-4cb9-a1cf-77aa6bf740af&region=jp-tok&serviceInstanceID=6f14a634-b459-4700-94f3-b109e0f10985)


## Features

The bot includes the following functionalities:

- **Schedule Vacation**: Employees can schedule their vacations directly via the bot, following a simple and automated process.
- **Payment Queries**: The bot provides information about payment schedules, payment methods, and other payment-related questions.
- **Benefits Questions**: Employees can inquire about the benefits provided by the company, such as health plans, meal allowances, etc.
- **Dress Code**: The bot answers questions regarding the company’s dress code policy, such as what is acceptable or not in the workplace.
- **Remote Work**: The bot responds to questions about remote work policies, including work hours, tools, and expectations.

## How It Works

The bot uses a **Retrieval-Augmented Generation (RAG)** model to provide responses. This approach involves:

1. **Document Retrieval**: The bot searches through relevant HR documents to find the most accurate and up-to-date information related to the query.
2. **Generative AI**: After retrieving the relevant information, the bot uses a generative model to formulate a personalized and context-aware response.

## JSON Structure

The JSON file defines the conversation flow, where the user's query is mapped to specific categories. Instead of hardcoded responses, the bot fetches relevant documents and uses a generative AI model to answer queries.
