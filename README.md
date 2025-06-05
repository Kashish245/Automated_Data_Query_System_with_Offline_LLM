# Automated Data Query System with Offline LLM

## Project Description
This system provides a natural language interface to query product data stored in MongoDB. It uses an offline Mistral-7B LLM to convert natural language questions into MongoDB queries, executes them, and returns results in CSV format. The solution meets all requirements specified in the GenAI Assignment PDF.

## Technical Stack
- **Backend**: Python 3.11
- **Database**: MongoDB Atlas
- **LLM**: Mistral-7B (offline via llama.cpp)
- **Libraries**: 
  - PyMongo (MongoDB interface)
  - LangChain (LLM integration)
  - Pandas (data processing)
  - Streamlit (optional UI)

## Assignment Requirements Fulfilled
- [x] CSV data loading to MongoDB
- [x] Natural language to MongoDB query conversion
- [x] Query execution and result display/saving
- [x] Implementation of 3 test cases
- [x] Query logging (Queries_generated.txt)
- [x] Error handling and validation
- [x] Documentation (this README)

## Setup Instructions

### Prerequisites
1. Google Colab account (recommended) or Python 3.11+ environment
2. MongoDB Atlas cluster (free tier available)
3. Minimum 8GB RAM (for LLM operation)

### Installation
1. Clone the repository or upload the notebook to Google Colab
2. Install dependencies:
```bash
!pip install pymongo sentence-transformers llama-cpp-python langchain python-dotenv pandas langchain-community
