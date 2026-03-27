# MOIT: Multi-Agent Hobby Matching Platform 

> **AI Agent-Based Hobby Matching Platform for Health Promotion**
> * Gold Prize, The 19th Capstone Design Competition (Soonchunhyang Univ.)*

##  Project Overview
**MOIT** is a personalized hobby matching platform powered by a Multi-Agent system. It is designed to address the limitations of conventional LLM agents—such as **premature termination** and **hallucination**—when dealing with ambiguous user queries. 

By utilizing **LangGraph (StateGraph)**, we engineered a robust architecture that strictly controls the agent's reasoning trajectory and integrates users' implicit contexts (e.g., psychological state, constraints) into the recommendation process.

---

##  My Role & Contributions
**Role:** Lead Developer & AI Agent Architect (`@Won-Gyu01`)

As the team leader and AI architect, I was responsible for designing and implementing the core Agentic AI pipeline:
* **Trajectory Control System:** Designed a deterministic routing architecture using LangGraph to prevent ReAct agents from stopping early without sufficient exploration.
* **Reasoning-Level Personalization:** Engineered an adaptive prompt framework that injects user survey data as hard constraints, guiding the agent to generate highly personalized reasoning steps.
* **RAG & API Integration:** Built a Retrieval-Augmented Generation (RAG) pipeline combining OpenAI APIs and **Pinecone vector database** to ensure factual consistency during the recommendation process.
* **Team Leadership:** Led version control, code integration, and overall project management among frontend/backend developers.

*( **Note:** You can find my core Agentic AI implementations in the **`html/AIAgent`** folder of this repository. Specifically, please check `main.py` and `Master_Agent.ipynb`.)*

---

##  System Architecture
<img width="877" height="771" alt="image" src="https://github.com/user-attachments/assets/5950c441-f916-40de-b81e-b4e38ab2ad29" />
<img width="504" height="955" alt="image" src="https://github.com/user-attachments/assets/a06cbf1b-38fb-4528-a318-ddfc683dc862" />
<img width="604" height="998" alt="image" src="https://github.com/user-attachments/assets/8a0036f1-5cc7-4313-8d11-7105fd3d2c34" />
<img width="867" height="539" alt="image" src="https://github.com/user-attachments/assets/dca3d08c-09bc-4140-8178-c8c28ea66012" />


---

##  Tech Stack
* **AI/Agent Framework:** LangChain, LangGraph, OpenAI API
* **Database:** Pinecone (Vector DB), MySQL
* **Language:** Python
* **[Other Stacks]:** (e.g., HTML, CSS, JavaScript, PHP)

---

##  Publications & Achievements
* **Paper:** "A Study on AI Agent-Based Hobby Matching Platform for Health Promotion" (Expected Dec 2025)
* **Awards:** *  **Gold Prize**, The 19th Capstone Design Competition (Soonchunhyang Univ.)
  *  **Bronze Prize**, 2025 Next-Generation Display Consortium Creative Capstone Design Competition (Chungnam National University, Korea)
