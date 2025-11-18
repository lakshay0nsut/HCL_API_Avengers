HEALTHIFY
#  Healthcare Wellness & Preventive Care Portal

A full-stack web application designed to help patients track wellness goals, manage preventive care, and enable healthcare providers to monitor patient compliance.  


---

##  1. Business Use Case

Develop a **Healthcare Wellness and Preventive Care Portal** that integrates seamless frontend and backend functionality, enabling:

- Wellness and preventive care tracking  
- Support for basic health goals  
- Compliance with preventive checkups  
- User-friendly and responsive design  
- Secure data handling with healthcare privacy standards  

---

##  2. Scope

The MVP focuses on delivering key modules demonstrating:

- Authentication & role management  
- Personalized patient dashboard  
- Preventive reminders  
- Goal tracking  
- Public health information page  
- Healthcare provider view  
- Basic security, logging, and compliance features  

---

##  3. Key Features Implemented

### **1. Secure Authentication System**
- Login & registration for patients and healthcare providers  
- JWT-based authentication  
- Password hashing with security measures  
- Consent checkbox for data usage  

---

### **2. Patient Dashboard**
- Wellness goals progress (steps, sleep, active time)  
- Preventive care reminders  
- “Health Tip of the Day”  
- Clean and responsive UI  

---

### **3. Profile Management**
- View/edit basic details  
- Includes allergies, medications, age, health info  

---

### **4. Healthcare Provider View**
- View all assigned patients  
- Compliance status overview (Goal Met / Missed Checkups)  
- Clickable patient list for insights  

---

### **5. Public Health Information Page**
- Static health resources:
  - COVID-19 updates  
  - Seasonal flu prevention  
  - Mental health awareness  
  - Privacy policy  

---

### **6. Goal Tracker for Patients**
- Steps input  
- Sleep tracking  
- Water intake logging  
- Daily progress view  

---

### **7. Privacy & Security Measures**
- User action logging  
- Role-based access control  
- Secure environment configurations  
- Basic HIPAA-like compliance measures  

---

## 4. Tech Stack

### **Frontend**
- React.js / Next.js  
- CSS Modules / Sass  

### **Backend**
- Node.js + Express  
- JWT Authentication  
- REST APIs  

### **Database**
- MongoDB Atlas / Firestore  

### **DevOps**
- Render (frontend/backend)

---

##  5. System Architecture

```
Frontend (React/Next.js)
   ├── Authentication
   ├── Dashboard
   ├── Profile
   ├── Provider View
   ├── Goal Tracker
   └── Public Info
       |
       v
Backend (Node.js + Express)
   ├── Auth Routes
   ├── Patient Routes
   ├── Provider Routes
   ├── Goal Routes
       |
       v
Database (MongoDB)
   ├── users
   ├── goals
   ├── reminders
   └── logs
```

---

## 📁 6. Folder Structure

```
project/
 ├── frontend/
 │    ├── src/
 │    ├── pages/
 │    ├── components/
 │    ├── services/
 │    └── styles/
 └── backend/
      ├── src/
      ├── controllers/
      ├── models/
      ├── routes/
      ├── middlewares/
      └── config/
```

---

##  7. Team Division (4 Members)

###  **Aarti – Frontend Lead**
- Login & Register pages  
- Dashboard UI  
- Public Info Page  
- CSS/Sass styling  

---

###  **Shubham – Backend Lead**
- Authentication APIs (JWT + hashing)  
- Patient & Provider APIs  
- Goal tracking APIs  
- Database models (User, Goals, Reminders)  

---

###  **Lakshay – Integration & DevOps**
- Connect frontend ↔ backend (Axios)  
- Role-based routing  
- Deploy frontend (Vercel) & backend (Render/Railway)  
- Environment variable setup  
- GitHub Actions workflow  

---

###  **Akshita – Core Features & Compliance**
- Profile Management module  
- Goal Tracker UI + integration  
- Logging system  
- Consent checkbox  
- Documentation & final presentation  

---
