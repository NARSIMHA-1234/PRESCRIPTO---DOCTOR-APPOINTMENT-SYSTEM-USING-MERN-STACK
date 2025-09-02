# 🏥 PRESCRIPTO – MERN Stack Doctor Appointment System  

A full-stack *MERN web application* that streamlines doctor appointment booking with *role-based access* (Patient / Doctor / Admin), secure payments (*Stripe & Razorpay), and a **responsive interface*.  

---

## 🚀 Tech Stack  
- *Frontend:* React.js  
- *Backend:* Node.js, Express.js  
- *Database:* MongoDB  
- *Authentication:* JWT (JSON Web Tokens)  
- *Payments:* Stripe, Razorpay  

---

## 🔑 Core Features  

### 👨‍⚕ Patient Portal  
- Register, log in, and book appointments  
- Manage bookings (view, cancel, reschedule)  
- Pay securely (Cash, Stripe, Razorpay)  
- Maintain a personal profile with editable details  

### 🩺 Doctor Dashboard  
- Manage appointments and view earnings  
- Access patient details for upcoming visits  
- Update availability, fees, and profile information  

### 🛠 Admin Panel  
- Add and manage doctors with full profile details  
- View analytics (doctors, patients, appointments)  
- Oversee and manage all bookings (cancel / mark completed)  

---

## 🏠 Home Page  
- Clean, user-friendly layout.  
- Search doctors by specialties.  
- View featured doctors and their profiles.  
- Additional sections: *About Us, **Delivery Information, **Privacy Policy, **Get in Touch*.  
- Footer with quick navigation links: Home, About Us, Delivery Info, Privacy Policy, Contact Us.  

---

## 🩺 All Doctors Page  
- Displays a list of all registered doctors.  
- Filter doctors by specialty.  
- Clicking a doctor’s profile opens the *Appointment Booking Page* with full details.  

---

## 📄 About Page  
- Showcases *Prescripto’s vision and mission*.  
- *Why Choose Us* highlights:  
  - ⚡ *Efficiency:* Quick and smooth appointment process.  
  - 🕒 *Convenience:* Book anytime with online payment options.  
  - 🎯 *Personalization:* Tailored experience based on preferences.  
- Footer with important links for easy navigation.  

---

## 📞 Contact Page  
- Displays office address and contact information.  
- Section to explore *career opportunities*.  
- Footer with navigation links.  

---

## 📅 Doctor Appointment Page  
- Shows doctor’s *profile picture, qualification, experience, and bio*.  
- Appointment booking form to select *date, time, and payment method*.  
- Multiple payment options: *Cash, Stripe, Razorpay*.  
- “Related Doctors” section at the bottom.  
- Requires login or account creation to confirm a booking.  

---

## 👤 User Profile  
- Accessible after login.  
- Features include:  
  - Upload profile picture.  
  - Update *name, email, address, gender, birthday*.  
  - View upcoming and past appointments.  
  - Logout option.  

---

## 🗄 Admin Panel  
- *Dashboard:*  
  - Shows statistics: number of doctors, appointments, patients, and recent bookings.  
  - Option to cancel bookings if necessary.  
- *Add Doctor:*  
  - Form to register new doctors (image, specialty, degree, experience, address, fees, description).  
- *Doctor List:*  
  - Manage existing doctors (edit / delete profiles).  
- *Appointments:*  
  - View all appointments with details (patient name, age, date, time, doctor, fees).  
  - Actions: Cancel or Mark as Completed.  

---

## 🩺 Doctor Dashboard  
- *Earnings Overview:* Displays total earnings from completed appointments.  
- *Appointments List:* Detailed list of patient visits (name, age, date, time, payment mode, status).  
  - Actions: Mark as Completed or Cancel.  
- *Profile Management:* Doctors can update description, fees, address, and availability.  


## 💳 Payment Integration  
- Multiple payment options: *Cash, Stripe, and Razorpay*  
- Secure and reliable checkout process  

---

## 🌐 Project Setup  

Follow these steps to set up and run the project locally:  

###   
bash
  1️⃣ Clone the Repository:
     git clone https://github.com/your-username/prescripto.git
     cd prescripto


  2️⃣ Install Dependencies:
     npm install
     cd client
     npm install


  3️⃣ Configure Environment Variables:
     Create a .env file in the root directory and add the following:
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     STRIPE_API_KEY=your_stripe_api_key
     RAZORPAY_API_KEY=your_razorpay_api_key


  4️⃣ Run the Application:
      npm run dev


## 📦 Folder Structure

```plaintext
prescripto/
├── client/          # Frontend (React.js)
├── server/          # Backend (Node.js, Express.js)
├── models/          # MongoDB Schemas
├── controllers/     # API Controllers
├── routes/          # API Routes
├── middleware/      # Authentication and Error Handling
├── config/          # Configuration Files
├── utils/           # Utility Functions
├── public/          # Static Files
└── .env             # Environment Variables
```



