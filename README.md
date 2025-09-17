# KnowledgeBase

“KnowledgeBase — a Document-driven Q&A platform”
Users upload documents (or create knowledge articles). The backend exposes robust REST APIs (CRUD, full-text search, tag/category filters, user auth, rate-limited chat endpoint). The AI part is a small chatbot endpoint that performs question answering over the stored documents using TF-IDF retrieval + simple answer-generation (fast, reproducible without external paid APIs). Frontend is a React app that demonstrates document management, search, and a chat UI.

Real-world backend skills: API design, auth (JWT), pagination, filtering, file upload, rate-limiting.
Testable: all endpoints testable in Postman and documented with Swagger/OpenAPI.
AI/ML: even a lightweight retrieval-based chatbot shows you can integrate ML/IR concepts into apps.
Frontend shows full-stack capability 
