# What is LangGraph?

LangGraph is a library for building stateful, multi-actor applications with LLMs. It extends the LangChain expression language with the ability to coordinate multiple chains (or actors) across multiple steps of computation in a cyclic manner.

## Core Concepts

*   **Graph:** A stateful graph that defines the flow of your application.
*   **Nodes:** The building blocks of the graph, representing a function or a chain.
*   **Edges:** The connections between nodes, defining the flow of data.
