# 🤖 Its ReAct Multifunctionality Agent 🚀

This project demonstrates a ReAct (Reason + Act) agent implemented using the Groq API and LLama 2 70b Chat model within a Jupyter Notebook environment. The agent is designed to perform various tasks by reasoning through a problem and taking appropriate actions.

## ✨ Features

- **ReAct Architecture:** Implements the ReAct pattern for agent decision-making.
- **Groq Integration:** Utilizes the Groq API for seamless interaction with LLama 2.
- **Tool Usage:** The agent can use predefined tools (e.g., calculator, planet mass lookup) to gather information.
- **Multi-Step Reasoning:** Can break down complex problems into smaller steps and solve them sequentially.
- **Jupyter Notebook Interface:** Provides an interactive environment for experimenting with the agent.

## ⚙️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AnonymousCoderArtist/MultifunctionCalling-ReAct-Agent.git 
   ```
2. **Set up Groq API Key:**
   - Create a `.env` file in the project root directory.
   - Add your Groq API key to the `.env` file:
     ```
     GROQ_API_KEY=your_groq_api_key
     ```

## 🚀 Usage

1. **Open the Jupyter Notebook:** Navigate to the cloned repository and open the `noice.ipynb` file in Jupyter Notebook.
2. **Run the notebook cells:** Execute the notebook cells sequentially to install dependencies, initialize the agent, and define the tools.
3. **Interact with the agent:** Use the `loop()` function to provide queries to the agent. The `loop()` function takes an optional `query` parameter as input.

## 📝 Example

The following example demonstrates how to ask the agent a question that requires multiple steps and tool usage:

```python
loop(query="What is the mass of Earth plus the mass of Saturn and all of that times 2?") 
```

The agent will then reason through the problem, use the `get_planet_mass` and `calculate` tools, and provide the final answer within the notebook output.

## 🤝 Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request on the GitHub repository.

