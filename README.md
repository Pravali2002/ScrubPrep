# ScrubPrep
📖 Story Behind the Project
My sister is currently preparing for her postgraduate medical exams — and like many med students, she's buried in mountains of textbooks. One evening, as she struggled to find a quick answer to a clinical question, my cousin casually said, "Why not use AI for that?" Her response? 😒 “AI doesn’t get medicine.”

Challenge accepted.

ScrubPrep was born out of a mission: to build an AI assistant that doesn't just guess, but actually knows — by pulling answers directly from her own medical textbooks. I wanted to prove that AI can help, when it's grounded in the right context.

ScrubPrep is a Retrieval-Augmented Generation (RAG) based chatbot that:
Accepts natural language medical questions 💬
Retrieves context from uploaded textbook content 📚
Generates accurate, relevant, and easy-to-understand answers ✨

⚙️ Tech Stack
LLM: Groq API / HuggingFace Transformers
RAG: LangChain + FAISS for semantic search
Vector Database: Pinecone for efficient semantic search and scalable vector indexing
Data: Custom-ingested medical textbooks (PDFs → chunks)
Frontend: Streamlit (quick UI for chat)
Backend: FastAPI (modular and scalable)

🧪 How I Evaluated It
I worked with my sister to test it using real PG exam-style questions. Evaluation focused on:
📌 Relevance to textbook content
📌 Clarity and conciseness of explanation
📌 Trustworthiness — no hallucinations allowed!

🎓 What I Learned
AI can be extremely helpful if it's grounded in the right data.
RAG architectures are incredibly powerful for domain-specific tasks.
Prompt engineering is just as important as model selection.
And most importantly... never underestimate a skeptical med student as a QA tester. 😉
