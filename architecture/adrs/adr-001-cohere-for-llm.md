## ADR 001: Cohere for LLM

## Context
We plan to develop a web application that automatically generates structured medical charts from voice recordings. To achieve this, we require an LLM capable of advanced text comprehension and structured data extraction.

In the early stages, hosting our own models would be inefficient and costly, so we will use LLM APIs instead. Several companies offer LLM APIs, including Cohere, OpenAI, Claude, and DeepSeek. Since our primary need is text understanding rather than complex reasoning or retrieval-augmented generation (RAG), any of these LLMs would suffice.

One key advantage of Cohere is that we have an existing partnership with them, allowing us to use their services for free in the coming months.

### Options
Cohere, OpenAI, Claude, DeepSeek

## Decision
We will use Cohere as our LLM API.

## Status
Accepted.

## Consequences
Using the Cohere API provides a significant cost advantage, as it is currently free for us. Since all LLM APIs use similar interfaces, we can easily switch to a different provider if we find another option better suited to our needs after our partnership period ends and Cohere incurs costs.