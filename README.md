<img src="./images/banner.png" width="800">

![GitHub last commit](https://img.shields.io/github/last-commit/llamaindex-ai/agentic-ai-course)
![GitHub repo size](https://img.shields.io/github/repo-size/llamaindex-ai/agentic-ai-course)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/llamaindex-ai/agentic-ai-course)
![GitHub Repo stars](https://img.shields.io/github/stars/llamaindex-ai/agentic-ai-course)
![GitHub top language](https://img.shields.io/github/languages/top/llamaindex-ai/agentic-ai-course)
[![Website](https://img.shields.io/badge/Visit-Website-blue)](https://www.llamaindex.ai)
[![Discord](https://img.shields.io/badge/Join-Discord-blue)](https://discord.gg/llamaindex)
[![Twitter](https://img.shields.io/badge/Follow-Twitter-blue)](https://twitter.com/llama_index)
[![YouTube](https://img.shields.io/badge/Subscribe-YouTube-red)](https://www.youtube.com/c/llamaindex)
[![LinkedIn](https://img.shields.io/badge/Follow-LinkedIn-blue)](https://linkedin.com/company/llamaindex)
[![GitHub](https://img.shields.io/badge/Follow-GitHub-black)](https://github.com/llamaindex-ai)

# Agentic AI with LlamaIndex Course

Welcome to our comprehensive Agentic AI Course using LlamaIndex! This course is designed for developers, data scientists, and AI enthusiasts who want to move beyond simple LLM applications and build sophisticated AI agents capable of reasoning, planning, and taking autonomous actions. Whether you're just starting with LLMs or looking to advance your skills in building autonomous AI systems, this course provides a structured learning path with practical, hands-on examples.

## Course Overview

Our course is structured into twelve carefully designed chapters:

- **Introduction to Agentic AI**: Understanding the evolution from passive LLMs to proactive AI agents
- **Fundamentals of LlamaIndex**: Core concepts and setup for building agent-based applications
- **Building Blocks of AI Agents**: Essential components that power autonomous systems
- **Designing Agent Workflows**: Strategies for creating effective reasoning and action patterns
- **Knowledge Retrieval for Agents**: Techniques for giving agents access to relevant information
- **Tool Use and Function Calling**: Enabling agents to interact with external systems and APIs
- **Conversational Agents**: Building natural dialogue systems with memory and context
- **Autonomous Planning and Execution**: Methods for goal-oriented behavior and self-correction
- **Agent Evaluation and Testing**: Frameworks for measuring and improving agent performance
- **Advanced Agent Architectures**: Exploring multi-agent systems and specialized designs
- **Ethical Considerations**: Responsible development practices and safety mechanisms
- **Capstone Project**: Building a full-featured agent that solves real-world problems

Each chapter combines theoretical foundations with practical implementation, allowing you to build working AI agents as you progress through the course.

## 🚀 What You'll Learn

By the end of this course, you'll be able to:

- Understand the fundamental differences between traditional LLMs and agentic AI systems
- Design and implement autonomous agents using LlamaIndex's powerful toolset
- Create agents that can reason, plan, and execute multi-step tasks
- Build systems that effectively retrieve and utilize knowledge
- Implement conversational agents with memory and personality
- Develop multi-agent systems where specialized agents collaborate
- Evaluate and improve agent performance using systematic testing
- Deploy agents responsibly with appropriate safety mechanisms

## 📋 Prerequisites

To get the most out of this course, you should have:

- Basic Python programming skills
- Familiarity with machine learning concepts
- Some experience with LLMs (though not required)
- A development environment with Python 3.8+ installed

## 📚 Learn with Us!

We offer multiple ways to engage with this course:

- **Self-paced learning**: Work through the Jupyter notebooks in this repository at your own pace
- **Community discussions**: Join our Discord community to ask questions and share insights
- **Live workshops**: Attend our scheduled virtual sessions for interactive learning
- **Office hours**: Get help from our instructors during dedicated support times

[<img src="./images/course-preview.png" width="800">](https://www.llamaindex.ai/courses/agentic-ai)

## 🚦 Getting Started

To begin your journey with Agentic AI:

1. Clone this repository: `git clone https://github.com/llamaindex-ai/agentic-ai-course.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Open the first notebook in the Chapter 1 directory: `jupyter notebook Chapter_1/Lecture_1.ipynb`
4. Follow along with the lectures and complete the exercises

## 💻 Code Examples

Each lecture includes practical code examples that you can run and modify. Here's a glimpse of what you'll be building:

```python
from llama_index.agent import ReActAgent
from llama_index.llms import OpenAI

# Create a simple reactive agent
llm = OpenAI(model="gpt-4")
agent = ReActAgent.from_tools(
    tools=[search_tool, calculator_tool],
    llm=llm,
    verbose=True
)

# Execute a task with the agent
response = agent.chat("What was the GDP of France in 2022 divided by its population?")
```

## 🤝 Contributing

We welcome contributions from the community! If you find bugs, have suggestions for improvements, or want to add additional examples:

1. Fork the repository
2. Create a new branch: `git checkout -b my-feature-branch`
3. Make your changes
4. Submit a pull request

## 📞 Contact Information

Feel free to reach out to us!

- 🌐 Website: [llamaindex.ai](https://www.llamaindex.ai)
- 💬 Discord: [llamaindex](https://discord.gg/llamaindex)
- 🎥 YouTube: [llamaindex](https://www.youtube.com/c/llamaindex)
- 🐦 Twitter: [llama_index](https://twitter.com/llama_index)
- 📧 Email: [hello@llamaindex.ai](mailto:hello@llamaindex.ai)
- 🎓 LinkedIn: [llamaindex](https://www.linkedin.com/company/llamaindex)
- 📚 GitHub: [llamaindex-ai](https://github.com/llamaindex-ai)

## 📄 License

This course is released under the MIT License. See the [LICENSE](LICENSE) file for details.
