## Agentic Design Patterns

### [Pattern 01 - Retrieval Augmented Generation (RAG) Agents](01-rag-agent/README.md)

RAG Agents are designed to retrieve information from a multitude of sources, including databases, documents, and APIs, and then use this information to generate an answer.

This pattern will focus on Retrieval from unstructured data, which comes with a lot of challenges including the need to understand the context to deliver on accuracy, performance and cost of operation.

We put RAG in perspective within the context of an Agentic AI System, to showcase how complex problems can be solved by a RAG enabled agent.

:rocket: [Retrieval Augmented Generation (RAG) Accelerator](../3_accelerators/01-rag-agent/README.md)

### [Pattern 02 - Code Generation Agents](02-code-generation-agent/README.md)

This pattern covers the design and implementation of agents that can generate code snippets, functions, or even entire programs based on a set of requirements. This pattern is particularly useful for developers who want to increase their productivity while respecting existing code standards, libraries, reference architectures, and best practices.

The applicability of a Code Generation Agent is vast, and we will cover the most common scenarios, namely:
- coding assistance
- code translation
- automated testing

:rocket: [Code Generation Agent Accelerator](../3_design_patterns_accelerators/02-code-generation-agent/README.md)

### [Pattern 03 - Multi-Domain Agents](03-multi-domain-agents/README.md)

This pattern discusses best practices to build Multi-Domain Agents that can understand and execute complex instructions accross a multitude of domains.

These agents are able to detect the domain of a request, handle domain switching and properly orchestrate requests to domain specific agents. They leverage a multitude of services accross domains to plan, evaluate, replan and achieve complex goals with potential human collaboration.

They also enable pausing tasks in one domain to switch to another domain and then resume the task in the original domain if needed to complete a complex workflow, or if directed by the user.

The pattern will cover some key-aspects of this pattern, including:
- domain scoping & detection, domain switching, request delegation
- long-running contextual memory: memorizing context accross domains to be able to resume task started in domain A when user switches to domain B and then back to domain A

:rocket: [Agentic Analytics Accelerator](../3_accelerators/03-multi-domain-agents/automating_analytics/README.md)