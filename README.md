# fashion-rag
someone wants to commission a fashion designer. this is a program, in the form of an LLM, that aims to generate a document to give to said fashion designer, based on personal preferences and characteristics.

## Architecture
MCP (Model Context Protocol) architecture will be used, as we do not have the time to create our own fresh LLM covering for all the functionalities of our project. We aim to utilize API keys of different LLMs to specialize in the functionalities of our project to maximize output quality. We are planning on using LangChain to set up the project's MCP architecture, and we plan on primarily utilizing ChatGPT. Once we gain a greater understanding of AI/ML overall, beyond surface level comprehension, we will strongly consider integrating other LLMs into our project as necessary.

## Backend
We're using Python with the Django library for intuitive full stack development. Our project will utilize document databases to enhance outputs for given prompts, utilizing their dictionary formats to integrate into our usage of Python. The backend will handle user auth (as in, signing in and saving chats with the LLM) and the connection of the LLM to the frontend for a seamless experience.

## Frontend
This will primarily be web design. Research needs to be done regarding this (to remove: not primary focus at the moment)

huckles
