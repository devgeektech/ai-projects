# AI Projects Portfolio

A collection of AI projects I've built. Each one is documented below with a short overview, features, and the stack used.

---

## Aria

**Repo:** [https://github.com/devgeektech/ai-aria](https://github.com/devgeektech/ai-aria)

Multi-tenant SaaS platform where businesses create and manage their own private AI assistant (Aria). Each tenant gets an isolated knowledge base, conversations, analytics, and AI config. End users can chat with a business's assistant over text or voice, and answers are grounded only in that business's documents.

### Features

- Three roles: Super Admin, Business Admin, and End User
- Super Admin can manage businesses, subscriptions, platform settings, and monitor usage across the system
- Business Admin can register a business, configure Aria, upload knowledge base docs, manage org users, and view conversation analytics
- End users can chat by text or voice, continue past conversations with context, and only see answers from that tenant's knowledge base
- Document uploads: PDFs, Word docs, text files, policies, manuals, FAQs, website content, and other business docs
- Full tenant isolation for knowledge bases, embeddings, conversations, analytics, and AI configuration
- RAG with hybrid retrieval (vector search + keyword search + metadata filters)
- Async document processing for uploads
- Voice conversations via Vapi
- Conversation memory across text and voice
- Usage tracking for tokens, voice, API costs, and conversation metrics
- Separate dashboards for Super Admin and Business Admin

### Tech Stack

**Backend & AI**
- Python, FastAPI
- PostgreSQL, SQLAlchemy, Alembic
- Pinecone, OpenAI Embeddings, OpenAI API
- Celery, Redis
- Vapi AI Voice Agent
- JWT auth with RBAC

**Frontend**
- Next.js, React, TypeScript
- Tailwind CSS, shadcn/ui
- TanStack Query, TanStack Table
- Recharts, Framer Motion, Zustand

---

<!-- Add more projects below as you go -->
