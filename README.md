# Bintang Pradana Erlangga Putra

## Profile

Backend engineer building tools and infrastructure that bridge distributed systems, machine learning, and programming language ecosystems. I work from Yogyakarta and contribute to open‑source projects across Go and Python.

- Website: [bpradana.github.io](https://bpradana.github.io)
- ORCID: [0000-0002-5406-067X](https://orcid.org/0000-0002-5406-067X)
- Twitter: [@Bintang_Pradana](https://twitter.com/Bintang_Pradana)
- LinkedIn: [in/bpradana](https://www.linkedin.com/in/bpradana)

## Selected Projects

### `facenet`
Production‑oriented FaceNet implementation in PyTorch. Implements triplet‑loss face recognition with modular data loading, distributed Lightning training, evaluation scripts, TorchScript export and a FastAPI inference service. Includes YOLO‑based face detection, configurable ResNet backbones and a Gradio recognition studio.

### `weave`
Go library for declarative orchestration. Allows defining tasks as plain functions with type‑safe inputs and outputs, automatically schedules them based on dependencies and exposes configurable failure strategies, context propagation, hooks and metrics. Supports pluggable dispatchers and DOT export for task graphs.

### `sequentialthinking`
Model Context Protocol (MCP) server enabling structured reasoning sessions. Provides in‑memory session store, branching, heuristics for logic validation and reasoning‑quality scoring, and tools to add or review analysis, hypothesis and verification steps. Supports stdio and HTTP transports with export capabilities.

### `inferno`
Lightweight Python inference server. Hosts multiple models with lazy loading and hot swapping, dynamic batching and concurrency controls, strict input validation via Pydantic, and structured logging and Prometheus metrics. Includes readiness/liveness endpoints and can share state across replicas via Redis.

### `goqs`
Modular quantum circuit simulator written in Go. Provides a pure Go state‑vector simulator, thread‑safe types and a declarative circuit builder for composing gates in parallel. Includes deterministic random seeds and example circuits demonstrating entanglement and superposition.

### `tars`
Unified interface for interacting with LLM providers. Implements providers for OpenAI, Anthropic, OpenRouter and Ollama; offers reusable templates with variable substitution, structured JSON output and strong typing. Provides validation, comprehensive error handling and an extensible architecture with functional options and factory patterns.

### `failsafe`
Resilience library for Go. Supplies flexible retry strategies (fixed delay, exponential backoff, jitter), circuit breaker and rate limiting middleware, metrics collection, async mode and generic result handling. Offers hooks for retry events, error filtering and runtime configuration updates.

### `sentinel`
High‑performance reverse proxy written in Go. Supports round‑robin, least‑connections and IP‑hash load balancing; configurable health checks; TLS termination with manual or Let’s Encrypt certificates; middleware for logging, rate limiting, authentication and compression; Prometheus metrics; and hot reload. Provides CLI tools for configuration validation and certificate generation.

### `contractor`
CLI tool that converts Ethereum smart contract ABIs into typed Web3.py contract wrappers. Handles single files or whole folders, auto‑names classes from filenames, generates type‑safe functions with gas estimation and receipt handling, and supports ABI input from file, string or URL
