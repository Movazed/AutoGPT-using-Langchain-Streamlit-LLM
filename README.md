# AutoGPT-using-Langchain-Streamlit-LLM
Introduction
LangChain is a framework for developing applications powered by language models. It enables applications that:

Are context-aware: connect a language model to sources of context (prompt instructions, few shot examples, content to ground its response in, etc.)
Reason: rely on a language model to reason (about how to answer based on provided context, what actions to take, etc.)
The main value props of LangChain are:

Components: abstractions for working with language models, along with a collection of implementations for each abstraction. Components are modular and easy-to-use, whether you are using the rest of the LangChain framework or not
Off-the-shelf chains: a structured assembly of components for accomplishing specific higher-level tasks
Off-the-shelf chains make it easy to get started. For complex applications, components make it easy to customize existing chains and build new ones.

Get started
Here’s how to install LangChain, set up your environment, and start building.

We recommend following our Quickstart guide to familiarize yourself with the framework by building your first LangChain application.

Note: These docs are for the LangChain Python package. For documentation on LangChain.js, the JS/TS version, head here.

Modules
LangChain provides standard, extendable interfaces and external integrations for the following modules, listed from least to most complex:

Model I/O
Interface with language models

Retrieval
Interface with application-specific data

Chains
Construct sequences of calls

Agents
Let chains choose which tools to use given high-level directives

Memory
Persist application state between runs of a chain

Callbacks
Log and stream intermediate steps of any chain

Examples, ecosystem, and resources
Use cases
Walkthroughs and best-practices for common end-to-end use cases, like:

Document question answering
Chatbots
Analyzing structured data
and much more...
Guides
Learn best practices for developing with LangChain.

Ecosystem
LangChain is part of a rich ecosystem of tools that integrate with our framework and build on top of it. Check out our growing list of integrations and dependent repos.

Additional resources
Our community is full of prolific developers, creative builders, and fantastic teachers. Check out YouTube tutorials for great tutorials from folks in the community, and Gallery for a list of awesome LangChain projects, compiled by the folks at KyroLabs.

Community
Head to the Community navigator to find places to ask questions, share feedback, meet other developers, and dream about the future of LLM’s.

API reference
Head to the reference section for full documentation of all classes and methods in the LangChain Python package.
