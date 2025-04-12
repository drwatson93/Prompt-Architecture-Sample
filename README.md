# AI Prompt Architecture Examples

This repository showcases two real-world examples of prompt systems I've architected as part of my work designing modular AI workflows. These prompts demonstrate how LLMs can be structured to decompose user intent, generate task-based workflows, and summarize structured data in business-facing formats.

The examples were created for AI-driven productivity and reporting tools, aligning closely with GoMode’s mission to orchestrate agentic systems that guide users from high-level goals to step-by-step execution.

---

## 📁 Contents

### `prompt_example_1_goal_decomposition.txt`
A structured prompt that transforms a user’s high-level goal (e.g., “launch a campaign”) into a nested hierarchy of benchmarks and tasks. Outputs are returned in clean JSON format, suitable for downstream use in task engines or AI agent matching layers.

- **Type**: Goal-to-task decomposition
- **LLM**: GPT-4 via OpenAI API
- **Features**: Modular JSON schema, benchmark/task logic tree, prompt refinement for context generalization

---

### `prompt_example_2_user_summary_genbi.txt`
A prompt designed for a GenBI-style system that turns structured tabular data into executive summaries. Used in internal reporting workflows to help product or marketing teams derive insights from user data.

- **Type**: Data-to-narrative generation
- **LLM**: GPT-4 via Azure OpenAI
- **Features**: Input schema parsing, narrative output tuning, tone control, metadata tagging

---

## 💡 Why These Matter
These prompt designs reflect:
- Systems thinking: inputs/outputs are structured for orchestration and agent chaining
- Real-world execution: prompts deployed and refined based on iterative testing
- Modularity: schema-first design that supports downstream agents or UI layers

They exemplify the kind of architecture required for scalable agentic AI platforms—matching tasks to the right agent, guiding the user clearly, and remaining adaptable as needs evolve.

---

📬 Interested in collaborating or seeing more examples? [Reach out here](mailto:mariomrtz93@gmail.com).
