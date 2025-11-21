# Agentic RAG with CrewAI

A multi-agent AI system powered by [crewAI](https://crewai.com) for building collaborative RAG (Retrieval-Augmented Generation) workflows. This project demonstrates how to orchestrate multiple AI agents that work together to research, retrieve, and synthesize information effectively.

## Overview

This template enables setting up a multi-agent AI system where specialized agents collaborate on complex research and knowledge retrieval tasks. Each agent has specific roles and responsibilities, maximizing collective intelligence and capabilities through the crewAI framework.

## Key Features

- **Multi-Agent Collaboration:** Multiple specialized agents working together on research tasks
- **RAG Integration:** Retrieval-augmented generation for accurate, context-aware responses
- **Flexible Configuration:** Easy customization of agents, tasks, and workflows
- **CrewAI Framework:** Leverages crewAI's powerful orchestration capabilities
- **Research Automation:** Automated research report generation on LLMs and AI topics

## Installation

Ensure you have Python >=3.10 <3.13 installed. This project uses [UV](https://docs.astral.sh/uv/) for dependency management.

First, install uv:

\\\ash
pip install uv
\\\

Navigate to your project directory and install dependencies:

\\\ash
crewai install
\\\

### Configuration

**Add your \OPENAI_API_KEY\ into the \.env\ file**

- Modify \src/agenticrag/config/agents.yaml\ to define your agents
- Modify \src/agenticrag/config/tasks.yaml\ to define your tasks
- Modify \src/agenticrag/crew.py\ to add your own logic, tools and specific args
- Modify \src/agenticrag/main.py\ to add custom inputs for your agents and tasks

## Running the Project

To kickstart your crew of AI agents:

\\\ash
crewai run
\\\

This initializes the Agentic RAG Crew, assembling agents and assigning tasks. By default, it creates a \eport.md\ file with research output on LLMs.

## Use Cases

- Research automation on AI/ML topics
- Multi-source information synthesis
- Collaborative document generation
- Knowledge base querying with agent orchestration

## Tech Stack

- **crewAI:** Agent orchestration framework
- **OpenAI API:** LLM capabilities
- **Python 3.10+:** Core implementation
- **UV:** Dependency management

Perfect for building production-grade multi-agent RAG systems with intelligent task delegation and collaborative workflows.
