# AI Agent Evaluation Framework

## Overview

This repository contains tools, techniques, and resources for evaluating AI agents in production environments. Based on the "Evaluating AI Agents" course by Andrew NG, johngilhuly, and amanberkeley, this framework helps you systematically assess and improve your AI agents before and during production deployment.

## Why Agent Evaluation Matters

When building AI agents for personal use or experimentation, efficiency metrics like API call count or reasoning steps might not seem important. However, in production:

- Each unnecessary API call increases costs
- Extra reasoning steps create higher latency
- Inefficient paths cause scaling problems

**What works in your notebook will often break in production.**

## Key Evaluation Methods

This repository implements three primary evaluation approaches:

1. **LLM as Judge Evaluation**
   - Quick assessment of agent outputs
   - Useful for initial quality checks
   - Configurable evaluation criteria

2. **Code-Driven Evaluation**
   - Automated testing of agent behaviors
   - Regression testing for agent improvements
   - Performance benchmarking

3. **Human Feedback Collection**
   - Structured feedback collection tools
   - Annotation interfaces for human evaluators
   - Feedback integration workflows

## Course Reference

This repository is inspired by the excellent "Evaluating AI Agents" course from DeepLearning.AI:
https://learn.deeplearning.ai/courses/evaluating-ai-agents/lesson/sqkza/introduction?courseName=evaluating-ai-agents

## Additional Resources

- **[Tracing and Evaluating AI Agents built with LlamaIndex's Workflows](https://github.com/run-llama/llama_index/tree/main/docs/examples/agent/agent_runner_openai_tracing.ipynb)**
- **[Evaluating a LangChain tool-calling agent](https://github.com/langchain-ai/langchain/blob/master/cookbook/agent_with_tool_retrieval.ipynb)** - [Video](https://www.youtube.com/watch?v=ahnGLM-RC1Y)
- **[Tracing and Evaluating LangGraph Agents](https://github.com/langchain-ai/langgraph/blob/main/examples/tracing/README.md)**
- **[Prompt template iteration for a summarization Service](https://github.com/promptengineering/promptflow)**
- **[Comparing Agent Frameworks](https://arxiv.org/abs/2308.03688)** - [Repository](https://github.com/microsoft/promptflow)
- **[Discussion of multi-agent framework with AutoGen](https://microsoft.github.io/autogen/)**
- **[Arize Phoenix Documentation](https://docs.arize.com/phoenix/)**

## Features

- 📊 Visualization tools for agent performance metrics
- 🔄 A/B testing framework for agent variations
- 🧪 Test suite generation for common agent tasks
- 📈 Performance tracking over time
- 🚨 Alerting for agent performance degradation
