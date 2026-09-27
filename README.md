# IISC-HACKATHON
The CodeForge AI-Adaptive Onboarding Engine is a precision-engineered learning pathway generator developed for the ARTPARK × IISc Hackathon. In the modern corporate landscape, "one-size-fits-all" onboarding is a relic that costs organizations millions in wasted productivity. Senior hires are forced through redundant basics, while junior recruits lack a structured bridge to advanced role requirements.

Our solution replaces static curricula with a dynamic, skill-gap-aware engine that ensures every minute of training is a minute spent closing a genuine competency gap.

# 🧠 Core Intelligence
The engine utilizes a Retrieval-Augmented Generation (RAG) architecture grounded in a verified course catalog. By parsing unstructured data from Resumes and Job Descriptions (JDs), the system builds a high-fidelity Skill Vector for both the candidate and the role.

Skill Gap Analysis: Using cosine similarity and semantic embeddings (BERT/Llama 3), the engine identifies "deltas"—the exact skills missing or requiring upskilling.

Knowledge Graph Traversal: Skills are not treated as isolated tags but as nodes in a Directed Acyclic Graph (DAG). Our path-planning algorithm performs a topological sort to ensure prerequisites are met before advanced modules are recommended.

Reasoning Trace (XAI): To ensure transparency for HR and leads, every recommendation includes a "Reasoning Trace," explaining why a specific module was selected based on the input documents.

# 🛠️ Tech Stack
Intelligence: Llama 3 / Claude 3.5 (Parsing), BERT (Embeddings), LangChain (RAG).

Vector Engine: FAISS for high-speed similarity search.

Backend: Python & FastAPI for a performant, asynchronous API layer.

Frontend: A high-fidelity, futuristic React UI powered by GSAP for fluid, state-driven animations.

Data: Grounded in O*NET datasets and grounded course ontologies to prevent LLM hallucinations.

# 🚀 Key Features
Zero-Redundancy Training: Matched skills are automatically bypassed.

Hallucination-Free: Recommendations are strictly bound to the provided course catalog.

Multi-Domain Scalability: Adapts from MLOps to Warehouse Logistics by simply swapping the skill ontology.

Explainable AI: Surfaces the logic behind the learning path in real-time.
