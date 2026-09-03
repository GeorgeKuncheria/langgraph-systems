# LangGraph Code

Workflow examples built with [LangGraph](https://langchain-ai.github.io/langgraph/): sequential, conditional, and parallel graphs.

```
Sequential_Workflows/
Conditional_Workflows/
Parallel_Workflows/
```

## Setup

### 1. Create a conda virtual environment

```bash
conda create -n langgraph-code python=3.11 -y
conda activate langgraph-code
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure API keys

Create a `.env` file in the project root with the keys you need:

```bash
OPENAI_API_KEY=your_key_here
GROQ_API_KEY=your_key_here
GOOGLE_API_KEY=your_key_here
```

### 4. Run the notebooks

```bash
jupyter lab
```

Then open any notebook under `Sequential_Workflows/`, `Conditional_Workflows/`, or `Parallel_Workflows/`.
