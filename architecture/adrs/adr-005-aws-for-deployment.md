## ADR 005: AWS for Deployment

## Context
VChart requires a scalable, secure, and HIPAA-compliant cloud infrastructure to host both the Next.js backend and frontend, along with AI-powered speech-to-text processing, medical chart generation, and database storage. The hosting solution must support high availability, security, and compliance with healthcare regulations (HIPAA, PHIPA, SOC 2) while ensuring low latency for medical professionals accessing patient data in real-time.

Since VChart is using Next.js for both frontend and backend, the cloud infrastructure must handle API requests, database interactions, and AI processing efficiently while maintaining security best practices for handling sensitive medical records.

### Options
AWS, Google Cloud, Microsoft Azure, Vercel

## Decision
We will use AWS to deploy our app. 

## Status
Accepted.

## Consequences
AWS provides a scalable and HIPAA-compliant infrastructure for hosting the Next.js backend, AI processing APIs, and MongoDB database, ensuring seamless data security and compliance. Vercel was chosen for frontend deployment due to its performance optimizations for Next.js, allowing server-side rendering (SSR) and static site generation (SSG), which improve frontend speed and SEO.