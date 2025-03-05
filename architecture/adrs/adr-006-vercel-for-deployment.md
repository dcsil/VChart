ADR 006: Vercel for Deployment
Context
VChart requires a scalable, secure, and HIPAA-compliant cloud infrastructure to host both the Next.js backend and frontend, along with AI-powered speech-to-text processing, medical chart generation, and database storage. The hosting solution must support high availability, security, and compliance with healthcare regulations (HIPAA, PHIPA, SOC 2) while ensuring low latency for medical professionals accessing patient data in real-time.

Since VChart is using Next.js for both frontend and backend, the cloud infrastructure must handle API requests, database interactions, and AI processing efficiently while maintaining security best practices for handling sensitive medical records.

Options
AWS, Google Cloud, Microsoft Azure, Vercel

Decision
We will use Vercel to deploy our app.

Status
Accepted.

Consequences
Vercel offers robust performance optimizations specifically designed for Next.js applications, such as efficient server-side rendering (SSR) and static site generation (SSG), which are crucial for delivering fast, SEO-friendly pages. The primary factor in choosing Vercel is cost: AWS proved to be expensive, and at this stage, we do not have sufficient funds to support its use. Vercel's free-tier option better aligns with our current budget constraints, allowing us to move forward without incurring high hosting costs. However, this change requires us to ensure that all security and compliance measures (previously aligned with AWS) are adequately addressed on the Vercel platform to meet HIPAA, PHIPA, and SOC 2 standards.
