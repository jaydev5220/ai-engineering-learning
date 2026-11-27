# 24-Week Applied AI Engineer Roadmap

**Start:** 30 November 2026 · **Target finish:** 16 May 2027  
**Career direction:** Applied AI Engineer; review fit after Weeks 8 and 16.  
**Approach:** self-paced, task-based, free resources, GitHub evidence.

## Phase map

1. **Weeks 1–3 — Python from scratch:** syntax, variables, data types, strings, conditions, loops, collections, functions, modules, OOP, files, exceptions, packages, virtual environments, typing, async, HTTP requests and pytest.
2. **Week 4 — Engineering foundations:** Git, Linux, HTTP, REST, FastAPI, SQL/PostgreSQL, Docker, logging and tests.
3. **Weeks 5–6 — Math, data and ML:** algebra essentials, statistics, NumPy, Pandas, scikit-learn, train/validation/test splits, metrics and model evaluation.
4. **Weeks 7–8 — Deep learning:** neural networks, forward/backpropagation, PyTorch, transformers and GPU basics.
5. **Weeks 9–10 — LLMs and training:** tokenization, embeddings, attention, transformer architecture, pretraining concepts, fine-tuning, LoRA/QLoRA, quantization and Hugging Face.
6. **Week 11 — Prompt and context engineering:** structured outputs, tool calling, context windows, token budgeting and memory.
7. **Weeks 12–13 — RAG:** ingestion, chunking, embeddings, vector search, metadata filters, hybrid retrieval, reranking, citations and retrieval evaluation.
8. **Weeks 14–16 — Agents:** tool use, workflows, LangGraph, state, memory, human approval, failure recovery and agentic RAG.
9. **Weeks 17–18 — MCP and harnesses:** MCP client/server, tools/resources/prompts, authorization, execution loops, persistence, observability and recovery.
10. **Weeks 19–20 — Inference and LLMOps:** model serving, Ollama/vLLM, latency, throughput, quantization, monitoring, versioning and deployment.
11. **Weeks 21–22 — Security, evaluation and system design:** prompt injection, data leakage, permissions, evaluation datasets, regression tests, caching, queues, scaling and high availability.
12. **Weeks 23–24 — Portfolio and career:** documentation, demo, architecture diagrams, deployment, resume, GitHub presentation and interviews.

## Free core resources

- Python: [Harvard CS50P](https://cs50.harvard.edu/python/) and [official Python tutorial](https://docs.python.org/3/tutorial/).
- Python practice: [Exercism Python](https://exercism.org/tracks/python).
- Data: [NumPy Learn](https://numpy.org/learn/), [pandas getting started](https://pandas.pydata.org/docs/getting_started/index.html).
- ML: [scikit-learn user guide](https://scikit-learn.org/stable/user_guide.html).
- Deep learning: [PyTorch tutorials](https://pytorch.org/tutorials/).
- LLMs: [Hugging Face course](https://huggingface.co/learn/llm-course).
- RAG and agents: [LangChain/LangGraph docs](https://docs.langchain.com/).
- MCP: [MCP official documentation](https://modelcontextprotocol.io/docs).
- System design: [freeCodeCamp system design principles](https://www.freecodecamp.org/news/learn-system-design-principles/).

Use the documentation as a reference, not as a reason to watch many courses at once. One primary resource per current topic.

## Week 1 — Python Fundamentals I (30 Nov–6 Dec)

**Primary course:** [Harvard CS50P](https://cs50.harvard.edu/python/).  
**Practice:** [Exercism Python](https://exercism.org/tracks/python).  
**Reference:** [Python tutorial](https://docs.python.org/3/tutorial/).

Complete in order whenever free time is available. See the detailed [Week 1 checklist](PYTHON/WEEK-01/README.md).

### Environment and first program
- [ ] Install Python 3 and record `python --version` in the Week 1 README.
- [ ] Install VS Code and the Python extension.
- [ ] Create and activate a virtual environment.
- [ ] Create and run `hello.py` from the terminal.
- [ ] Practice `print()` and comments; commit `output_and_comments.py`.

### Variables and types
- [ ] Learn variable assignment and naming; create `variables.py`.
- [ ] Understand `str`, `int`, `float`, `bool`; create `data_types.py`.
- [ ] Learn `type()` and type conversion; create `type_conversion.py`.
- [ ] Practice arithmetic operators; create `calculator.py`.

### Strings and input
- [ ] Learn concatenation and f-strings; create `strings.py`.
- [ ] Learn indexing, slicing and common string methods; create `string_operations.py`.
- [ ] Learn `input()` and safe numeric conversion; create `user_profile.py`.

### Mini-project and review
- [ ] Build a terminal personal-profile app using variables, types, strings and input.
- [ ] Test normal input and at least two invalid input cases.
- [ ] Explain the concepts in your own words.
- [ ] Push Week 1 code and update [PROGRESS.md](PROGRESS.md).
- [ ] Complete [Week 1 review](WEEKLY-REVIEWS/WEEK-01.md).

**Week 1 exit criteria:** create, run and explain small Python scripts independently. Do not advance merely because the week ended.

## Phase exit gates

- **Python:** write small scripts without copying; understand errors and debug them.
- **Engineering:** build and test a small FastAPI service.
- **ML:** explain data splits and select appropriate metrics.
- **Deep learning:** explain forward pass, loss and gradient descent.
- **LLMs:** explain tokens, embeddings, attention and fine-tuning trade-offs.
- **RAG:** demonstrate grounded retrieval and measure retrieval quality.
- **Agents:** demonstrate tool use, state, approval and failure handling.
- **MCP:** run an MCP server and safely expose a small set of tools.
- **Production:** benchmark, monitor and secure a model-backed service.
- **Career:** explain design decisions and demonstrate projects in a live walkthrough.
