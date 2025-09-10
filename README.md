# SafeTrail
# 🛡️ Smart Tourist Safety Monitoring & Incident Response System  
**AI-powered safety platform using Geo-Fencing, Blockchain-based Digital Identity, and Real-Time Incident Response**

---

## 📖 Overview
Tourist safety is a critical challenge in crowded or unfamiliar environments. Traditional systems rely heavily on manual reporting and delayed response times.  

This project leverages **AI, Geo-fencing, and Blockchain** to provide a **real-time safety ecosystem** that:  
- Detects incidents (manual SOS + AI-powered fall/scream detection).  
- Monitors tourist movement in high-risk zones using **geo-fencing**.  
- Issues **verifiable digital IDs** via blockchain to enable secure identity validation.  
- Provides a **real-time responder dashboard** for authorities to take action.    

---

## 🎯 Core Features
### 📱 Tourist Mobile App
- Manual **SOS button** with live location sharing.  
- **Geo-fencing alerts** when entering unsafe areas.  
- (Future) AI-powered distress detection (fall/scream).  
- Secure **Digital ID wallet** (blockchain-based verifiable credentials).  

### 🚓 Responder App
- Real-time **SOS notifications**.  
- Accept & track incidents.  

### 🌐 Admin Dashboard
- Live map of incidents and geo-fences.  
- Incident timeline & responder management.  
- Geofence creation & analytics.  

---

## 🛠️ Tech Stack  

### **Frontend**  
- **React Native** – Cross-platform development for Tourist & Responder mobile applications.  
- **React.js** – Web-based Admin Dashboard for real-time monitoring and analytics.  
- **Tailwind CSS** – Modern, responsive UI design and styling.  

### **Backend & APIs**  
- **Node.js + Express.js** – Core backend framework and REST API development.
- **Flask** – Lightweight Python framework to serve ML model responses to the mobile application.
- **Socket.io** – Real-time communication for SOS alerts and live location tracking.  
- **Python (Planned AI Module)** – For implementing advanced distress detection features such as fall recognition and scream detection using machine learning.  

### **Database & Storage**  
- **MongoDB** – Storage and management of user, incident, and responder data.  
