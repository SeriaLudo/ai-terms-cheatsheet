# AI Terms Cheatsheet

## LLM (Large Language Model)
A trained neural network that generates text based on input prompts. Examples: GPT-4, Claude, Gemini.

## RAG (Retrieval-Augmented Generation)
Technique where an LLM retrieves relevant context from a knowledge base before generating a response.

## MCP (Model Context Protocol)
An open protocol that standardizes how AI applications connect to data sources and tools.

## Fine-tuning
The process of training a pre-trained model on domain-specific data to improve its performance on specific tasks.

## Prompt Engineering
Crafting effective inputs to LLM to get desired outputs. Includes techniques like few-shot learning, chain-of-thought.

## Embedding
Numerical representation of text (vectors) that capture semantic meaning, used for similarity search.

## Hallucination
When an LLM generates confident but factually incorrect information.

## Temperature
Parameter controlling randomness in LLM output. Higher = more creative, lower = more deterministic.

## Token
The smallest unit of text an LLM processes. ~4 characters = 1 token.

## Context Window
The maximum amount of text an LLM can consider at once (input + output).

## System Prompt
Instructions given to an LLM that define its behavior, role, and constraints.

## Function Calling
Ability of LLMs to invoke external tools/APIs based on user requests.

## Guardrails
Safety mechanisms to prevent harmful outputs or enforce policy compliance.

## Agent
An LLM equipped with tools and autonomy to complete multi-step tasks autonomously.

## Prompt Injection
Malicious input designed to override system prompts or extract sensitive information.

## Grounding
Providing factual context to an LLM to reduce hallucinations and improve accuracy.

## Hugging Face
Open-source ML platform and model hub. Hosts thousands of pre-trained models and datasets.

## Harness
Software infrastructure that wraps around an LLM/agent, handling tool execution, memory/context management, and orchestration – everything except the model itself. Think of it as the "body" that gives the AI "hands and memory."