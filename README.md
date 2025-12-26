# NyayBuddy - AI Legal Assistant

> **Your AI-powered companion for navigating Indian legal matters**

NyayBuddy is a comprehensive legal assistance platform designed specifically for Indian citizens to understand their legal rights, generate legal documents, and connect with verified lawyers - all powered by advanced AI technology.

## 🌟 Overview

NyayBuddy democratizes access to legal knowledge and services in India by providing AI-powered tools that help users:

- Analyze their legal cases and understand their options
- Generate professional legal documents (notices, emails)
- Chat with an AI legal assistant in English/Hindi (Hinglish)
- Find and connect with verified lawyers based on location and case type
- Track their cases and communicate with legal professionals

## ✨ Key Features

### 🔍 NyayScan - AI Case Analyzer

- **Smart Case Analysis**: Upload your case details and get instant AI-powered legal analysis
- **Multi-lingual Support**: Available in English and Hindi (हिंदी)
- **Detailed Insights**: Receive comprehensive analysis including:
  - Case type identification
  - Legal provisions and relevant laws
  - Step-by-step action plan
  - Cost estimates and timelines
  - Success probability assessment
  - Past similar cases for reference
- **Document Upload**: Attach relevant documents (receipts, emails, contracts) for better analysis
- **Interactive Q&A**: AI asks targeted follow-up questions to understand your case better

### 📧 NyayMail - Legal Email Generator

- Generate professional legal emails to companies and organizations
- Auto-detect company contact details from knowledge base
- Include legal references and relevant consumer protection laws
- Set appropriate deadlines and demands
- Professional formatting and language

### 📜 NyayNotice - Legal Notice Generator

- **Self-Drafted Legal Notices**: Generate legally compliant notices without a lawyer
- **Intelligent Issue Detection**: AI analyzes your problem description and applies correct legal provisions
- **Step-by-Step Form**: Easy multi-step form for collecting all necessary details
- **Comprehensive Notices**: Includes:
  - Proper legal format with sender/recipient details
  - Statement of facts with dates
  - Relevant legal grounds (Consumer Protection Act, IPC sections, etc.)
  - Clear demands and relief sought
  - Response deadline and consequences
- **Company Details Auto-Fill**: Automatically fetches registered office details
- **Download as PDF**: Generate and download professional PDF notices
- **Sending Instructions**: Guidance on how to send via Speed Post/Registered Post

### 💬 Snehh (स्नेह) - AI Legal Chatbot

- **Friendly Legal Companion**: Chat in English or Hinglish for comfortable interaction
- **Multi-Purpose Assistance**:
  - General legal guidance on Indian law
  - App navigation help
  - Consumer rights information
  - Legal procedure explanations
  - FIR filing guidance
- **Real-time Streaming**: Fast, conversational AI responses
- **Always Available**: 24/7 legal assistance at your fingertips

### 👨‍⚖️ Find Lawyers

- Search verified lawyers by:
  - Location (city/state)
  - Case type (Consumer, Property, Criminal, Family, etc.)
- View lawyer profiles with:
  - Expertise areas
  - Experience
  - Contact information
- Save favorite lawyers for later
- Direct communication channel

### 📱 My Cases

- Track all your cases in one place
- Chat with assigned lawyers
- Upload case documents
- Receive updates and notifications
- Lawyer feedback system

### 📚 Additional Features

- **Legal Dictionary**: Search and understand legal terms in simple language
- **Notifications**: Stay updated on case progress
- **Privacy Settings**: Control your data and preferences
- **Dashboard Settings**: Customize your experience

## 🛠️ Technologies Used

### Frontend

- **React 18** with TypeScript for type-safe development
- **Vite** for lightning-fast builds and HMR
- **React Router DOM** for seamless navigation
- **TanStack React Query** for efficient data fetching and caching

### UI Components & Styling

- **shadcn/ui** - Beautiful, accessible component library
- **Radix UI** - Headless UI primitives for accessibility
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Beautiful icon library
- **next-themes** - Theme management
- **Sonner** - Elegant toast notifications

### Backend & Database

- **Supabase** - Backend-as-a-Service
  - PostgreSQL database
  - Authentication & user management
  - Edge Functions for serverless API
  - Real-time subscriptions

### AI Integration

- **AI Gateway** - Powered by Google Gemini 2.5 Flash model
- **Edge Functions**:
  - `snehh-chat` - AI chatbot with streaming responses
  - `nyayscan` - Case analysis and categorization
  - `nyayscan-detailed` - In-depth case analysis with Q&A
  - `nyaymail` - Email generation
  - `nyaymail-reply` - Reply email generation with image analysis
  - `nyaynotice` - Legal notice generation
  - `lawyer-chat-ai` - Lawyer-client chat assistance
  - `generate-case-summary` - Case summary for lawyers

### Document Processing

- **jsPDF** - PDF generation for legal notices
- **File Upload & Processing** - Support for images, PDFs, documents

### Form Handling

- **React Hook Form** - Performant form management
- **Zod** - TypeScript-first schema validation
- **@hookform/resolvers** - Form validation integration

## 📋 Prerequisites

- **Node.js** (v16 or higher) - [Install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
- **npm** or **yarn** package manager
- **Supabase Account** - For backend services

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <YOUR_GIT_URL>
cd nyay-companion-ai
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Environment Setup

Create a `.env` file in the root directory with the following variables:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_PUBLISHABLE_KEY=your_supabase_anon_key
```

### 4. Start Development Server

```bash
npm run dev
```

The application will be available at `http://localhost:8080`

### 5. Build for Production

```bash
npm run build
```

## 📱 User Roles

### For Citizens (Users)

- Analyze legal cases with AI
- Generate legal documents
- Chat with AI legal assistant
- Find and connect with lawyers
- Track case progress

### For Lawyers

- Receive case summaries from NyayScan
- Chat with clients
- Manage multiple cases
- View client documents
- Provide professional feedback

## 🔒 Security & Privacy

- End-to-end encrypted communication
- Secure authentication via Supabase
- Data stored in compliance with Indian data protection laws
- No legal advice disclaimer - all information is for guidance only
- User data privacy controls

## 🌐 Deployment

This project can be deployed to various platforms:

## 🌐 Deployment

This project can be deployed to various platforms:

- **Vercel** - Recommended for React applications
- **Netlify** - Simple deployment with CI/CD
- **Azure Static Web Apps** - Enterprise-grade hosting
- **AWS Amplify** - Full-stack deployment

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.

## ⚠️ Disclaimer

**IMPORTANT**: NyayBuddy is an informational tool and does NOT provide legal advice. All information provided is for general guidance only and should not be considered as a substitute for professional legal counsel. For specific legal matters, always consult a qualified lawyer.

## 📞 Support

For questions or issues, please open an issue on GitHub or contact the development team.

---

**Made with ❤️ for the citizens of India**
