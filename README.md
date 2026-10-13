Act as a Principal Solutions Architect at Microsoft. 
Here is my hackathon problem statement:
[PASTE COMPLETE PROBLEM STATEMENT]

In a single response, provide:
1. MVP Scope: 3 core features required for a working prototype vs. lower-priority features.
2. Recommended single-file Python backend stack (FastAPI + SQLite) and a lightweight frontend (Streamlit or single-file HTML/Tailwind).
3. Cloud Architecture Mapping: How this maps to Microsoft Azure enterprise components (App Services, Azure SQL, Entra ID, Key Vault, Azure Monitor).
4. Step-by-step implementation roadmap for 2 hours of development.



Based on the architecture above, provide the COMPLETE, production-ready backend code in a single file `app.py`.
Requirements:
- FastAPI with CORS enabled for all origins.
- SQLite with SQLAlchemy or pure sqlite3.
- Automatically seed the database on startup with 6 realistic enterprise records so the demo is never empty.
- Fully implemented CRUD endpoints for our 3 MVP features.
- No omitted code, no '// TODO' comments. Write out every single line ready to run with `uvicorn app:app --reload`.


Write a complete single-file frontend (`index.html` with Tailwind CSS CDN and Vanilla JS fetch calls, OR a full `dashboard.py` in Streamlit) that interfaces with the `app.py` endpoints.
Requirements:
- Polished, enterprise Microsoft-style dashboard (clean card metrics, status badges, data table).
- Working modal or form to create a new record that updates the table live without page reload.
- Status indicator showing API connection health.
- Complete, runnable code with zero placeholders.



Generate a formal Technical Architecture Document (TAD) for this solution that I can copy directly into Microsoft Word. Format it with clean headers and enterprise terminology:
1. Executive Summary & Problem Framing (Business value & ROI).
2. End-to-End System Architecture (Client Layer -> API Layer -> Database Layer).
3. Microsoft Azure Ecosystem Mapping (Detailing Azure App Service, Azure Entra ID for RBAC, Azure Key Vault, Azure Cosmos/SQL, Azure Monitor).
4. Security & Compliance (Data encryption at rest/in transit, audit logging, least-privilege access).
5. Scalability & Disaster Recovery Strategy.


Generate slide content for a 6-slide executive presentation in PowerPoint. For each slide, provide the Slide Title, 3-4 bullet points, and an explicit Speaker Script:
- Slide 1: Enterprise Problem & Industry Pain Points
- Slide 2: The Solution & Business Value Proposition
- Slide 3: Solution Architecture & Azure Alignment
- Slide 4: Prototype Capabilities & Walkthrough Flow
- Slide 5: Security, Governance & Enterprise Compliance
- Slide 6: ROI, Implementation Roadmap & Next Steps



