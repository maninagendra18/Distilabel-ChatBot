# Distilabel Chatbot using Anthropic Claude 3 Haiku

This project is an AI chatbot built using a Distilabel pipeline integrated with the Anthropic Claude 3 Haiku model. It generates responses dynamically based on user instructions and supports both predefined dataset inputs and real-time user queries.

##  Features

* Pipeline-based text generation using Distilabel
* Integrated with Anthropic Claude 3 Haiku model
* Processes custom dataset instructions
* Supports interactive user input for dynamic response generation
* Implemented and tested in Google Colab

##  Tech Stack

* Python
* Distilabel
* Anthropic API
* Google Colab

##  Model Used

This project uses the **Anthropic Claude 3 Haiku** model, a fast and efficient large language model for generating responses.

* Model Name: `claude-3-haiku-20240307`
* Capabilities: Instruction following, basic reasoning, code generation
* Used via Anthropic API inside the Distilabel pipeline

##  Project Workflow

1. Created a sample dataset with user instructions
2. Built a Distilabel pipeline using a TextGeneration task
3. Integrated Claude 3 Haiku model for response generation
4. Executed pipeline to generate outputs for dataset
5. Extended functionality to accept real-time user input

##  Example

**Instruction:**
Help me set up my daily to-do list

**Generated Output:**
Python code that allows users to create and manage a to-do list dynamically

---

##  How to Run

1. Install dependencies:

   ```bash
   pip install distilabel[anthropic] anthropic pydantic
   ```

2. Set your API key:

   ```bash
   export ANTHROPIC_API_KEY=your_api_key
   ```

3. Run the notebook in Google Colab

---

## Key Learnings

* Understanding of LLM-based text generation
* Working with Distilabel pipelines
* Integrating external APIs (Anthropic Claude)
* Handling structured datasets and user-driven inputs

---

##  Author

Mani Nagendra

