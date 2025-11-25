# Dmitry Starodubtsev
Full-stack engineer building AI-powered hiring platforms and high-load B2B systems.

## Professional Work
**Software Developer Intern @ APS Data Technologies** | April 2024 - Present  
Building production AI-powered ATS systems processing 1000+ applications daily for K-12 school districts.

### Key Systems I've Built (Under NDA)

**AI-Powered Application Screening System** → [**See Demo**](https://github.com/stdmitry04/aps-main-demo)
- RAG-based chatbot with vector embeddings for intelligent document processing
- OCR pipeline extracting structured data from unstructured documents (transcripts, resumes, letters)
- Automated applicant routing reducing manual review time by 60%
- Tech: Next.js, Django, Qdrant, OpenAI API, Docker

**Admissions & Onboarding Platform** → [**See Demo**](https://github.com/stdmitry04/campus-usa-demo)
- React/Next.js platform supporting 500+ concurrent users with 99.9% uptime
- Real-time interview scheduling with automated email workflows
- Multi-stage offer management with role-based permissions
- Tech: Next.js, Django, PostgreSQL, AWS (EC2, S3, RDS), Docker

**📊 Impact:** Processing 1000+ applications/day across multiple school districts. System maintains 99.9% uptime during peak hiring seasons (Aug-Oct).

> ⚠️ **Note:** The full production systems are proprietary. The demo repositories show core architectures I built:
> - [**campus-usa-demo**](https://github.com/stdmitry04/campus-usa-demo): AI document processing & RAG chatbot
> - [**aps-main-demo**](https://github.com/stdmitry04/aps-main-demo): Applicant tracking & hiring workflows
>
> Production systems include additional microservices, enterprise integrations (DocuSign, ERP), and multi-tenant infrastructure not shown in demos.

---

## Demo Repositories

### [AI Application Processing System](https://github.com/stdmitry04/campus-usa-demo)
**What I built and can show:**
- RAG chatbot with vector embeddings (Qdrant)
- OCR pipeline for document extraction (transcripts, PDFs)
- Django REST API with OpenAI integration
- Essay & Letter Of Recommendation scoring systems
- Document processing workflows

**What's under NDA:**
- Production-scale vector database configuration
- Multi-district data isolation
- Enterprise document storage (AWS S3 + compliance)
- Automated scoring/routing algorithms

### [Applicant Tracking Platform](https://github.com/stdmitry04/aps-main-demo)
**What I built and can show:**
- Templated Offer System: Dynamic offer letter generation with {{field}} placeholder extraction, template preview API, and real-time field auto-population
- Custom Position Creation: Built from scratch or template-based with multi-stage interview configuration, screening question M2M relationships, and nested serializer patterns (InterviewStage → Interviewer hierarchy)
- Onboarding Workflow: Token-based candidate access system with 8-section form progression, JSONField data storage, document verification pipeline, and comprehensive audit logging
- Advanced Django Patterns: List vs Detail serializers, district-isolated multi-tenancy via ForeignKey + middleware, auto-populated nested writes with perform_create() overrides
- RESTful API Design: Custom actions (@action decorators) for workflow state transitions, public/authenticated endpoint splitting, and complex filtering (Q objects, date ranges, stage progression)


**What's under NDA:**
- DocuSign/ERP integrations
- Production AWS infrastructure (Terraform configs)
- Automated email/notification workflows
- Multi-tenant architecture patterns

These demos represent **~30-40% of each full system**—focusing on core functionality I architected and implemented.

---

## Other Public Projects
### [QuiKard](https://github.com/stdmitry04/quikard) | [Live Demo](https://quikard.net)
Generate personalized business cards in under 1 minute, export QR code to Apple Wallet in 1 click.
- Tech: Next.js, TypeScript, TailwindCSS

### [CourseChecker](https://github.com/neontap/spartahack)
College course review aggregator built at SpartaHack X hackathon.
- Tech: React, Node.js

---

## Tech Stack
**Frontend:** React, Next.js, TypeScript/JavaScript, TailwindCSS  
**Backend:** Django REST Framework, FastAPI, Node.js  
**AI/ML:** OpenAI API, RAG systems, Qdrant vector DB  
**Infrastructure:** AWS (EC2, S3, RDS), Docker, Terraform, PostgreSQL, Redis  

---

## Education
**Michigan State University** | B.S. Computer Science, Business Minor | Expected May 2026  
GPA: 3.8 | Focus: Distributed Systems, AI/ML, High Performance Computing

---

📫 **Contact:** [LinkedIn](https://linkedin.com/in/stdmitry04) | starodu5@gmail.com
