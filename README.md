# 🎬 ClipRanker

**Multimodal Video Search and Ranking Engine using CLIP + FAISS**

ClipRanker is a semantic video search system that allows users to search short video clips using natural language. It leverages [OpenAI's CLIP](https://github.com/openai/CLIP) to generate embeddings for both video frames and user queries, and uses [FAISS](https://github.com/facebookresearch/faiss) for efficient vector similarity search.

The project simulates TikTok-style content discovery by:
- Matching user queries to relevant videos using semantic similarity
- Supporting real-time ranking and retrieval
- Optionally modeling personalization through user preference simulation

## 🔧 Tech Stack
- CLIP (via `sentence-transformers`)
- FAISS for vector search
- OpenCV for frame extraction
- Streamlit for UI
- Python (NumPy, Pillow, etc.)

## 📦 Use Cases
- Multimodal search engines
- Video recommendation research
- Prototype for short-form video discovery platforms

> 🚧 In active development – dataset integration, personalization modeling, and batch inference coming soon!
