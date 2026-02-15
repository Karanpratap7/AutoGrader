# High Level Architecture

```
Pull Request
    ↓
GitHub Action (self-hosted runner)
    ↓
Python script
    ↓
Call http://localhost:11434
    ↓
Ollama model responds
    ↓
Post review comment
```