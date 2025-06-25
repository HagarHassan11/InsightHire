# InsightHire

https://github.com/user-attachments/assets/14a4ce32-ca56-40b2-b00a-da3c3112b770

## 🚀 Key Features

*   **📄 Multi-Format Document Ingestion**: Upload multiple CVs at once in **PDF**, **PNG**, **JPG**, or **JPEG** formats.
*   **🧠 Agentic Query Decomposition**: Breaks down complex user queries (e.g., "Find me AI engineers with Python and TensorFlow experience who have also led a team") into distinct, searchable sub-queries.
*   **🔍 High-Precision Retrieval**: Uses a FAISS vector index for fast and efficient similarity search across all documents for each sub-query.
*   **🤖 Critical Relevance Verification**: A secondary "Verifier" LLM agent critically assesses each retrieved text chunk to ensure it contains **explicit, unambiguous evidence** for the sub-query, drastically reducing noise and false positives.
*   **📊 Structured & Synthesized Output**: A final "Synthesizer" LLM agent aggregates all verified evidence and presents the result in a clean Markdown table, directly answering the user's original query.
*   ** transparency**: Detailed logs in the sidebar show exactly which chunks were retrieved, how they were scored, and the LLM's verification verdict, providing full transparency into the AI's reasoning process.
