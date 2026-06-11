# ContractIQ — AI-Powered Contract Analysis Platform

## Project Highlights
This specific repository has been pre-configured to run **100% offline** and locally for demonstration, portfolio, and hackathon presentation purposes. 

The entire Supabase backend (Authentication, Database, and Storage) has been securely mocked in the `src/integrations/supabase/client.ts` layer using your browser's `LocalStorage`. This means anyone who downloads this project can instantly start using it without provisioning cloud databases or setting up API keys!

## Tech Stack
- **Frontend**: React 18, TypeScript, Vite, Tailwind CSS
- **UI Components**: shadcn/ui (Radix UI primitives)
- **Local Backend Engine**: LocalStorage Mock Adapter (Zero-Config)
- **State Management**: TanStack React Query
- **Routing**: React Router DOM v6
- **Charts**: Recharts

## How to use this project

### 1. Prerequisites
Ensure you have Node.js 18+ installed on your system.

### 2. Installation
Clone the repository and install all Node dependencies:
```bash
git clone https://github.com/AHMAD-ANAS-P-S/ContractIQ.git
cd ContractIQ
npm install
```

### 3. Running the Application
Start the frontend Vite development server:
```bash
npm run dev
```
Open your browser and navigate to `http://localhost:8080/` (or the port specified in your terminal).

### 4. Testing the Platform
- **Signup / Login**: Because the backend is fully simulated, you can simply type any email/password to create an account. You will be instantly redirected to the dashboard. If you logout, you must use that exact same password to sign back in!
- **Demo Data**: Once inside the dashboard, click the "Load Demo Data" button to instantly populate the application with mock contracts, clauses, and analytics for presentation purposes.
- **Templates**: The application comes pre-loaded with 5 natively mocked contract templates.
- **Offline Capability**: You do not need an active internet connection, database connection, or API keys.

---
## Features
- ✅ Email/password simulated authentication
- ✅ Protected dashboard routes
- ✅ Side-by-side contract comparison
- ✅ Global search (Ctrl+K / Cmd+K)
- ✅ Contract template management (5 pre-loaded presets)
- ✅ Dashboard and chart analytics
- ✅ Settings (profile, security, notifications)

## License
Private — All rights reserved.
