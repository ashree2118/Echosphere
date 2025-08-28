# 🌐 **Echosphere – AI-Powered Property Management Platform**

**Echosphere** is a modern property management solution that connects **residents, property owners, and maintenance staff** through an **AI-powered, voice-enabled platform**. It simplifies community living by streamlining **issue reporting, service requests, and management workflows**.  

---

## 🎥 Demo Video
▶ [](https://vimeo.com/1113959172?share=copy)
<img width="1814" height="914" alt="image" src="https://github.com/user-attachments/assets/323b542a-0edc-41ba-a797-365a64006bd7" />

---

## 🏗️ Tech Stack

- **Frontend**: React 19 + TypeScript + Vite + Tailwind CSS  
- **Authentication**: JWT + bcrypt  
- **UI Components**: Radix UI + shadcn/ui  
- **Styling & Animations**: Tailwind CSS + Framer Motion  
- **Voice Features**: Custom voice chat + NLP integration  

---

## ✨ Core Features

### 👥 Multi-Role User System
- **Residents** → Report issues, request services, view events  
- **Property Owners** → Manage properties, approve requests, oversee staff  
- **Technicians** → Handle assigned tasks, update status, communicate  

---

## 🖼️ Screenshots
<img width="1152" height="834" alt="image" src="https://github.com/user-attachments/assets/3f3d71a2-b9ab-47a7-9de5-b0cf2867da4b" />
<img width="1631" height="726" alt="image" src="https://github.com/user-attachments/assets/1e20de94-4220-4e16-ae32-f07e4e83d0f7" />


---

### 🛠️ Issue Management System
- **Types**: Plumbing, Electrical, HVAC, Security, Internet, Appliances, Structural, Pest Control  
- **Priorities**: P1 (Critical) → P4 (Low)  
- **Workflow**: `Pending → Assigned → In Progress → Resolved`  
- **Attachments**: Multiple image uploads for documentation  

---

### 🧾 Service Request System
- **Services**: Cleaning, Repair, Maintenance, Installation, Inspection  
- **Workflow**: `Pending → Awaiting Approval → Approved → Assigned → In Progress → Completed`  
- **Approval**: Owner approval required before assignment  

---

### 🎙️ Voice-Enabled Features
- **Voice Assistant**: AI-powered conversational interface  
- **Commands**: Raise issues, check status, request services  
- **NLP**: Converts speech into structured, actionable requests  

---

### 📊 Dashboard Interfaces

#### 🏢 Owner Dashboard (`/dashboard/owner`)
- Property & staff management  
- Approve/assign issues & service requests  
- Community event planning  
- AI assistant for admin tasks  
- Stats & analytics overview  

#### 🏠 Resident Dashboard (`/dashboard/resident`)
- Profile management  
- Voice assistant for quick actions  
- Issue reporting & service requests  
- Event calendar & history tracking  

#### 🔧 Technician Dashboard
- Assigned task tracking  
- Status updates in real-time  
- Communication with residents/owners  
- Manage availability  

---

## 🚀 Development Setup

### Frontend (Client)
```bash
cd client
npm install
npm run dev
```

### Backend (Server)
```bash
cd server
npm install
npm run dev
```

### Database
```bash
cd server
npx prisma generate
npx prisma db push
```

## 🔐 Security Features

- **JWT Authentication**: Secure token-based authentication
- **Password Hashing**: bcrypt for password security
- **Input Validation**: Zod schema validation
- **CORS Configuration**: Cross-origin resource sharing setup
- **Helmet**: Security headers middleware


This repository represents a modern, scalable property management platform with AI-powered features designed to streamline community management and enhance resident experience. 
