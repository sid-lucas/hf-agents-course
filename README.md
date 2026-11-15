# Hugging Face AI Agents Course

Personal notes and exercises from the [Hugging Face AI Agents Course](https://huggingface.co/learn/agents-course), with a focus on how agents work under the hood and where the security risks are.

## Setup

The course notebooks rely on the Hugging Face Inference API, which is no longer free. The exercises here run locally instead, using [Ollama](https://ollama.com) and its OpenAI-compatible endpoint.

```bash
ollama pull qwen2:7b
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Structure

```
unit1/   Fundamentals: LLMs, chat templates, tools, Thought/Action/Observation loop
```

## Progress

- [x] Local environment (Ollama + Python venv)
- [ ] Unit 1: dummy agent, step by step
- [ ] Unit 1: first agent with smolagents
- [ ] Unit 2: agent frameworks