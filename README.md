# 🏫 Campus Mirador — Augmented Reality Campus Guide

## 📱 Overview
**Campus Mirador** is an **Augmented Reality–based mobile application** designed to help users explore university buildings interactively.  
The app integrates **Unity AR** for real-time building visualization and **a cross-platform front-end** for smooth user interaction.  

The project was developed as a **Final Year Project (FYP)** with a focus on:
- **Human–Computer Interaction (HCI)** principles  
- **Accessibility** for users of all ages  
- **Integration of Augmented Reality (AR)** to enhance campus navigation  

---

## 🧩 Key Features
- 🎯 **AR Building Detection** — Automatically identifies campus buildings using the device camera  
- 🧠 **Chatbot Support** — Integrated with ChatGPT to answer user queries about classrooms, faculty, and offices  
- 📊 **Statistics Dashboard** — Displays detailed insights about campus buildings and users  
- 💬 **Feedback System** — Collects user suggestions for continuous improvement  
- 🌐 **Cross-Platform Compatibility** — Android version built and tested  
- 👁️ **Accessible Design** — Large fonts, readable colors, and simple navigation  

---

## 🎨 Human–Computer Interaction Focus
The UI consists of **8 intuitive screens** designed for readability and ease of navigation:  

### 🏠 Welcome Screen
Displays introductory text.  
Pressing **Continue** redirects the user to the Sign-Up page.  

### 📝 Sign Up Screen
Users can:
- **Sign Up** using their institutional email (student/faculty/visiting faculty)  
- **Continue as Guest** using a Gmail account  

Upon successful authentication:
- Guests → redirected to the **Home Page**  
- Registered Users → redirected to the **Login Page**  

### 🔐 Login Screen
Simple credential-based login supporting:
- Domain email / username + password  
- **Google login** for visitors  
Additional features:
- “Remember me” cookies  
- Password reset  
- Help page access via the 🔍 Help icon  

### 🏡 Home Screen
Central hub of the app offering two main options:
1. **Scan Building** — Opens the AR scanner  
2. **View Statistics** — Displays user and building analytics  

### 🏗️ Scan the Building Screen
Allows users to point their camera at a building.  
A trained model identifies one of three classes:
- **SEECS UG Block**  
- **SEECS PG Block**  
- **IAEC Building**

After identification, users proceed to the **AR Overlay Screen**.  

### 🌍 AR Overlay Screen
Core AR feature displaying **classrooms, offices, and amenities** inside the detected building.  
Users can explore interior details virtually via augmented reality.  

### 📈 Statistics Screen
Shows analytical data about:
- Building categories  
- User activity  
- Floor and room distribution  

Presented using a mix of **numerical data and descriptive text**.  

### 🧭 Explore More Screen
Provides extended building information such as:
- Dean name  
- Available floors  
- Classroom count  
- Office details and facilities  

### 🤖 Chatbot Screen
Integrated **ChatGPT-powered chatbot** answering queries related to:
- Campus navigation  
- Faculty offices  
- Classroom details  

### 🗣️ Feedback Screen
Enables users to share comments and suggestions for future improvements.  

---

## 🧱 Technology Stack
| Component | Technology |
|------------|-------------|
| Front-end | Java, XML (Android UI), JavaFX |
| AR Integration | Unity 3D (AR Foundation / ARCore) |
| Back-end | Java APIs / Firebase Authentication |
| Database | Firebase Realtime Database |
| Chatbot | ChatGPT API |
| IDEs Used | NetBeans, IntelliJ IDEA, Unity Editor |

---

## ⚙️ Architecture Overview
The project follows an **object-oriented architecture** with **13 Java classes**, **7 image assets**, and **1 media file**, implementing:
- **Encapsulation**
- **Inheritance**
- **Polymorphism**
- **Abstraction**

---

## 🎮 Demonstration Flow
1. **Launch** the app → Welcome Screen  
2. **Sign Up / Login** using institutional or Google account  
3. **Scan** a campus building using the camera  
4. **View AR Overlay** of the detected structure  
5. **Access Statistics**, **Explore More**, or **Chat with the Bot**  
6. **Submit Feedback**  

---

## 🔊 Additional Features
- Background music with on/off and volume controls  
- Multi-theme support  
- Comprehensive inline code comments  

---

## 🎓 Learning Outcomes
- Deep understanding of **Object-Oriented Programming (OOP)** concepts  
- Hands-on experience with **Java & JavaFX GUI development**  
- **Unity AR integration** with mobile apps  
- Experience handling **media files and animations**  
- Improved grasp of **human–computer interaction principles**

---

## 🧠 Future Enhancements
- Full iOS support  
- Advanced AR markerless tracking  
- Real-time navigation assistant  
- Enhanced chatbot responses using LLMs  

---

