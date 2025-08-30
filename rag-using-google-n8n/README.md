# RAG using Google Drive (n8n)

This folder contains the n8n workflow for a Retrieval-Augmented Generation (RAG) system that integrates with Google Drive.

## Files

- **RAG using Google Drive-n8n.json**: n8n workflow export
- **image.png**: workflow diagram/screenshot (to be added)

## Overview

This workflow implements a RAG system that:
- Connects to Google Drive to retrieve documents
- Processes and indexes the content for retrieval
- Generates responses using AI models
- Provides intelligent document search and Q&A capabilities

## 🧩 Components Used

### Core Nodes
- **Google Drive Download Node**: Retrieves documents from Google Drive
- **Pinecone Node**: Vector database for storing and querying embeddings
- **Small Embedding Node**: Generates vector embeddings for document chunks
- **OpenAI API Node**: Powers the AI generation and processing
- **Simple Memory Buffer Node**: Maintains conversation context and memory
- **AI Agent Node**: Orchestrates the RAG workflow and decision making

### Workflow Architecture
- Document retrieval from Google Drive
- Text chunking and embedding generation
- Vector storage in Pinecone database
- Intelligent retrieval based on semantic similarity
- AI-powered response generation with context

## Setup

1. Import `RAG using Google Drive-n8n.json` into your n8n instance
2. Configure Google Drive API credentials
3. Set up Pinecone API key and environment
4. Configure OpenAI API credentials
5. Set up the necessary webhook endpoints
6. Configure document processing parameters
7. Test with sample queries

## Features

- Document retrieval from Google Drive
- Intelligent content indexing with embeddings
- Vector-based semantic search
- AI-powered question answering
- Automated document processing
- Scalable RAG architecture
- Memory persistence for conversations
- Real-time document updates
