👋 Hi, I'm Abhijeet
Full Stack Developer · B.Tech @ NIT Tiruchirappalli
I build production-grade web systems — from real-time applications to
institutional infrastructure. Currently working at the Centre for Digital
Infrastructure (CDI), NIT Trichy, where I design and deploy systems used
by the entire institute.
🏗️ What I'm Building at CDI, NIT Trichy
🔐 NITT Auth Service — Centralized SSO Platform
A production-ready authentication system serving as the single identity
provider for all NIT Trichy web applications.

Passwordless OTP login via institutional @nitt.edu email
JWT access tokens (15 min) + refresh tokens (7 days) with rotation
Redis-backed OTP storage and session management
HTTP-Only cookie architecture — XSS-safe token handling
OAuth2-style Authorization Code exchange flow for cross-domain SSO
Role detection from email patterns (Student, Faculty, HOD, Director...)
Docker + Nginx deployment on campus infrastructure
Audit logging, rate limiting, Helmet.js security headersStack: Node.js · Express · PostgreSQL · Prisma · Redis · React · Vite · Docker · Nginx
🚪 NITT Gate Pass System
A role-based visitor and gate pass management system for campus security.

Multi-role workflow: Faculty → HOD → Security approval chain
QR code generation and scanning for entry/exit
Real-time status tracking via HTTP polling
Integrated with NITT Auth SSO for seamless loginStack: Node.js · Express · PostgreSQL · React · Tailwind CSS
💻 Tech Stack


