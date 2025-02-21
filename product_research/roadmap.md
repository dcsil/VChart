# Roadmap

As we move forward with developing our AI-powered EMR system, our strategic roadmap outlines key milestones across three phases: short-term (MVP development), medium-term (feature expansion and compliance research), and long-term (market readiness and full-scale deployment). Our primary goal is to build an intuitive, AI-driven solution that enhances efficiency for nurses and doctors while ensuring security and compliance.

This roadmap details the critical steps required to achieve our vision, from setting up core infrastructure and AI-powered charting to integrating with existing hospital systems and securing funding for long-term growth. By following this structured plan, we aim to deliver a cutting-edge EMR solution that streamlines documentation, reduces administrative burden, and improves healthcare outcomes.

## Short Term

**Duration:** Q1 2025

Goal: Build and deploy MVP with AI-powered charting, database setup, and backend services.

Key Milestones

- Infrastructure Setup: GitHub repo, MongoDB Atlas, AWS Lambda, Next.js API routes.
- AI Integration: Assemble AI for speech-to-text, Cohere AI for chart generation.
- Testing & Security: Unit testing, API validation, security measures (encryption).
- User Research & MVP Refinements: Gather early feedback from nurses.
- MVP Completion (April 9): Deploy for internal testing and limited beta users.

Given that as of February 20, we have completed:

- GitHub Setup
- Hello World App in Chosen Framework
- UX & User Research (gathered insights from nurses/doctors)
-  UX Prototype Design

### Feb 20 - Feb 29 (Week 6-7)
- Test Infrastructure Setup
- CI/CD Setup (GitHub Actions)
- Deploy Initial Web App to Production
- Set Up Sentry & External Logging
- Set Up Next.js API Routes for:
  - User authentication (JWT-based login, signup)
  - Patient data storage & retrieval (MongoDB schema)
  - Chart entry storage (voice-to-text transcriptions)
  
- Start Speech-to-Text Integration (Basic Flow)
  - Set up Whisper AI / Google STT API
  - Store transcribed notes in MongoDB

### March 1 - March 10 (Week 8-9)
- Implement Basic Frontend UI

- Auto-structure transcriptions into formatted charts

- Build Quick Chart Review & Editing Feature
  - Nurses can view Pending Review notes
  - Implement basic text editor for reviewing & modifying AI-generated notes
    
- Implement Patient Management (Basic CRUD)
  - Nurses can add/remove patients
  - Ensure data updates in real-time

 - Begin Security Setup
  - Encryption for stored transcriptions
    
### March 11 - March 20 (Week 10-11)
-  AI Charting Enhancements
  - Add auto-saving & timestamping for every note

- Export Functionality (PDF/Email)
  - Nurses can finalize charts & export them

- Security & Compliance (More Focus Now)
  - Implement audit logging for access/modifications
  - Ensure HIPAA-compliant encryption (end-to-end)

 - Early Testing with Internal Users
  - Get feedback from nurses/doctors on workflow usability
  - Fix critical UX bugs
    

### March 21 - April 5 (Week 12-13)

- Fix Bugs & Optimize Performance
  - Address all issues from internal testing
  - Optimize API response times & database queries

- Final UI/UX Polish
  - Improve mobile responsiveness & UI clarity
  - Ensure seamless workflow for nurses

### April 6 - April 9 (Final Stretch)

- Do a full walkthrough from login to exporting a chart
- Fix final bugs & small UI issues
- Prepare for Beta Launch (Docs & Guides)
- Write quick user guides for first testers
- Ensure deployment is smooth

  MVP COMPLETE ON APRIL 9!


## Medium Term

**Duration:** Q3 2025

Goal: Expand MVP features, improve AI accuracy, conduct user testing, and start compliance research.

Key Milestones

- Improve AI Model Performance: Optimize transcription accuracy & structured charting.
- Enhance Security & Compliance Research: Identify HIPAA/PHIPA certification needs, security upgrades.
- Expand User Testing: Onboard additional beta users, refine workflows based on feedback.
- Develop Web Dashboard: Doctor interface for reviewing/editing AI-generated charts.
- Integration with existing EMR systems

## Long Term

**Duration:** 2026

Goal: Finalize compliance, integrate with existing hospital systems, secure funding, and prepare for full public launch.

Key Milestones

- Complete Compliance Implementation: Work with legal experts, complete security audits.
- Integration with existing hospital systems: Develop FHIR-compliant API connections.
- Funding & Business Expansion: Raise seed funding, form hospital partnerships.
- Public Launch Prep (April 2026): Transition from beta to full market release.
