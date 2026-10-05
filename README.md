# Parth Abhang

I build and evaluate applied AI systems, from tool-using LLM agents and reproducible benchmarks to compact, domain-specialized models that run offline. The emphasis throughout is on systems that can be measured, verified, and trusted.

Currently an AI Engineer at [Flam](https://www.flamapp.com).

### Focus areas

- **LLM agents and tool use:** agent loops, evidence verification, and trajectory data for distillation
- **Evaluation and benchmarking:** reproducible, spec-driven test environments for agentic systems
- **Model specialization:** fine-tuning, quantization, and how compression affects factual reliability
- **Applied ML:** RAG, NLP, and computer vision, plus speech and generative media in production
- **ML infrastructure and product engineering:** containerized pipelines, observability, and full-stack delivery

### Selected work

| Project | Description |
| :-- | :-- |
| [rootcause_agent](https://github.com/Parth080/rootcause_agent) | LLM agent that diagnoses the root cause of a Kubernetes incident from a single symptom line, using read-only access to metrics, logs, traces, and cluster state. It runs a hand-rolled tool-use loop, with a second verifier pass that checks the evidence supports the diagnosis. |
| [rootcause_benchmark](https://github.com/Parth080/rootcause_benchmark) | Reproducible benchmark of realistic Kubernetes incidents for evaluating root-cause agents, built on the OpenTelemetry Demo, a microservice application spanning ten language runtimes. Each incident is a declarative YAML spec: what to break, what on-call sees, the true root cause, and how to restore. |
| [pocketrights](https://github.com/Parth080/pocketrights) | Offline, domain-specialized model for Indian legal information, designed to answer from its own weights with real Act and Section citations and to refuse out-of-domain questions. Research question: how aggressive quantization degrades citation validity, numeric fidelity, hallucinated authority, and refusal behaviour relative to surface fluency. In progress. |
| [gpu_tracker](https://github.com/Parth080/gpu_tracker) | Self-hosted dashboard for tracking a team's GPU instances across Modal, Vast.ai, and Runpod. Built with Next.js, TypeScript, Drizzle ORM, and Turso; deployed on Vercel. |
| [careloop](https://github.com/Parth080/careloop) | Personal AI assistant for older adults and their caregivers. In active development. |
| [FlavourCraft](https://github.com/Parth080/FlavourCraft_main) | AI recipe generator that detects ingredients from photos and suggests recipes. Dockerized with an MLOps pipeline; built by a four-person team. |

Earlier public repositories cover machine learning, NLP and deep learning, generative AI, and computer vision, along with PDF and SQL chatbots and full-stack web applications.

### Stack

- **ML and LLMs:** Python, PyTorch, TensorFlow/Keras, Hugging Face, LangChain
- **Infrastructure:** Docker, Kubernetes, OpenTelemetry, AWS, Vercel, Git
- **Product engineering:** TypeScript, Next.js, React, Node.js/Express, Tailwind, PostgreSQL, MongoDB

### Contact

[LinkedIn](https://www.linkedin.com/in/parth-abhang-76619025b) · [X](https://twitter.com/Parth010504) · [abhangparth@gmail.com](mailto:abhangparth@gmail.com)
