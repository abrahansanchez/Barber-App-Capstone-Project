# BarberConnect – Smart Appointment & Communication Platform for Barbers

## Project Overview

**BarberConnect** is a full-stack web application designed to help barbers manage appointments and client communication in a more efficient, accessible, and automated way. It eliminates the need for a receptionist or assistant by providing a visual dashboard for barbers and a phone-based voice menu for clients — powered by technologies like **Twilio** for voice and SMS automation.

---

##  Core Features (MVP)

### Voice-Activated Menu (via Twilio Voice API)
Clients can call a dedicated number and interact with the following phone menu:
- **Press 1** to book an appointment  
- **Press 2** to hear availability  
- **Press 3** to cancel  
- **Press 4** to speak to their barber  

### Client Interface (Web or Mobile UI)
- Calendar-style or list view of available times  
- Simple, visual booking system  
- Ability to cancel or rebook appointments  

### Barber Dashboard
- Visual calendar of upcoming appointments  
- Set custom hours and availability  
- View and manage client info and bookings  

### Appointment Reminders (via Twilio SMS)
- Clients receive SMS reminders 30–60 minutes before their appointment  

---

## Accessibility & Simplicity

- Designed with elderly clients and non-English speakers in mind  
- Language toggle support (e.g., English/Spanish)  
- Clean UI with large text and intuitive voice interaction  

---

## Tech Stack

### Frontend
- React.js for dashboard and client booking interface  
- Tailwind CSS for styling  
 

### Backend
- Node.js + Express.js for server and routing  
- MongoDB for data persistence  

### Integrations & APIs
- **Twilio Voice API** – phone-based interactive voice menu  
- **Twilio SMS API** – automatic text appointment reminders  
- **Google Calendar API** *(optional)*  

### Authentication
- Firebase / Auth0 / JWT for secure barber login  

---

## Stretch Goals / Premium Features
- Multi-barber support for full barbershop usage  
- Custom voicemail or pre-recorded message playback  
- Client booking history and loyalty tracking  
- Analytics dashboard for premium barbers  

---

##  Real-World Use Case

Barbers often juggle calls, texts, and reschedules during appointments. **BarberConnect** solves this by:
- Replacing a full-time assistant  
- Enabling client self-service by phone or web  
- Saving time and reducing no-shows  

---

## Future Business Model

- **Free Tier:** 1 barber, limited SMS/month  
- **Pro Tier:** Unlimited barbers, custom prompts, shop branding  
- **Admin Portal:** Multi-barber team management for barbershops  

---

## Capstone Requirements Checklist

| Requirement                          | Status |
|-------------------------------------|--------|
| Full-stack application              | ✅     |
| Real-world use case                 | ✅     |
| External API integration (Twilio)  | ✅     |
| Authentication system              | ✅     |
| CRUD operations                     | ✅     |
| MVP + Scalable features             | ✅     |
| Accessibility considerations        | ✅     |
