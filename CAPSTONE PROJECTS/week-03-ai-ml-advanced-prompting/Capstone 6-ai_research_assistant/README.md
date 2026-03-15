Project Scenario 2: AI Research Assistant for Students
A university wants to build an AI-powered Research Assistant that can help students quickly understand long academic articles and generate structured insights.

The system should be able to:

Summarize long text


Extract key insights


Answer questions about the content


Generate concise explanations


You are required to design and implement a prototype using a Large Language Model (LLM).

Task 1 – LLM Interaction Setup (5 Marks)
Use any LLM API such as:

Gemini


OpenAI


HuggingFace Transformers


Steps:

Write Python code to send a text prompt to an LLM.


Provide a sample long article or research paragraph.


Generate a summary using the LLM.


Deliverable:

Python code


Input text sample


Generated output


Task 2 – Prompt Engineering Experiments (8 Marks)
Design and test three different prompting strategies.

1️⃣ Zero-Shot Prompt
Ask the model to summarize the article without providing examples.

Example task:

Summarize the following article in 5 bullet points.

2️⃣ Few-Shot Prompt
Provide 2 example summaries before asking the model to summarize a new article.

3️⃣ Chain-of-Thought Prompt
Ask the model to reason step-by-step before generating the summary.

Example structure:

Analyze the article step by step:

1. Identify the main topic

2. Extract key ideas

3. Generate a concise summary

Deliverable:

All three prompts


Model outputs


Comparison of responses


Task 3 – Prompt Optimization (7 Marks)
Improve the prompt so that the AI generates better executive summaries.

Your optimized prompt must produce:

3 key insights


1 actionable takeaway


Professional tone


Test the optimized prompt on two different articles.

Deliverable:

Final optimized prompt


Two example outputs


Task 4 – Tokenization Experiment (5 Marks)
Use a tokenizer from HuggingFace or any LLM library.

Steps:

Tokenize a paragraph of text.


Count the total number of tokens.


Display the tokenized output.


Example tools:

tiktoken


transformers tokenizer


Deliverable:

Python code


Token count


Example tokenized output


Task 5 – Build a Mini AI Tool (5 Marks)
Create a simple AI assistant that takes a long article and produces:

A short summary


Key insights


One actionable recommendation


The program should:

Accept text input


Send prompt to LLM


Display structured output


Deliverable:

Python script or notebook


Example result
