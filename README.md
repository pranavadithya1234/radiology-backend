Radiology AI Portal - Backend
A high-performance, intelligent backend system powering the Radiology Portal. This robust Node.js/Express service integrates multiple AI models (Google Generative AI, Hugging Face), Redis caching, and real-time socket communications to process, analyze, and manage complex radiological data and medical reports securely.

🚀 Key Features
AI Integration: Direct integration with Google Generative AI (Gemini) and Hugging Face inference endpoints for advanced medical image and text analysis.
Real-time Communication: Built-in Socket.IO support for instant notifications and live updates to connected frontend clients.
High-Performance Caching: Redis integration via connect-redis for blazingly fast session management and request caching.
Secure File Handling: Robust file upload and management system using Multer and Cloudinary for secure storage of radiological scans.
Automated Reporting: Generates downloadable PDF reports on-the-fly using pdfkit.
Authentication & Security: JWT-based authentication, password hashing with bcryptjs, and secure session handling.
Email Notifications: Automated email delivery system utilizing nodemailer.
🛠️ Technology Stack
Core Engine: Node.js (>= 18.0.0), Express.js
Database: MongoDB (Mongoose ORM)
Caching & Sessions: Redis, express-session
AI & ML: @google/generative-ai, @huggingface/inference, groq-sdk
Storage: Cloudinary, Multer
Real-time: Socket.IO
Utilities: Axios, Winston (logging), PDFKit
