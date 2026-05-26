# Writeups

This repository collects short technical writeups and their source files. The intent is to keep the authored material in version control while avoiding generated LaTeX artifacts, so the repo mostly contains PDFs and images.

## Current Writeups

### A Systems-Oriented Introduction to Modern Retrieval

Files: [`systems_oriented_introduction_to_modern_retrieval/systems_oriented_introduction_to_modern_retrieval.pdf`](./systems_oriented_introduction_to_modern_retrieval/systems_oriented_introduction_to_modern_retrieval.pdf)

This writeup explains modern retrieval from a systems perspective. It starts with the retrieval problem itself, builds through lexical and semantic search, introduces embeddings and vector databases, and then moves into retrieval-augmented generation, reranking, and later-stage system concerns such as quantization, evaluation, query planning, agentic retrieval workflows, and graph-enhanced retrieval.

### Voltage vs Current Control

Files: [`voltage_vs_current_control/voltage_vs_current_control.pdf`](./voltage_vs_current_control/voltage_vs_current_control.pdf)

This writeup explains why current control is usually a better abstraction than raw voltage control when you want predictable motor torque. It starts from the motor equation, shows how back-EMF changes the amount of current a fixed voltage can actually produce, and contrasts the two important operating cases: stall and motion. The core argument is that because torque is proportional to current, current control gives a more direct and bounded way to command mechanism effort, especially for something like an intake that may alternate between moving freely and getting stuck.
