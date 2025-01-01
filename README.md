
# **HackTrek: Vulnerable Web Application**

## **Overview**  
**HackTrek** is a learning platform designed to help security enthusiasts and professionals understand and exploit common web application vulnerabilities. Built using the **MERN** (MongoDB, Express.js, React.js, Node.js) stack, HackTrek provides hands-on challenges that simulate real-world security flaws, enabling users to hone their penetration testing skills in a safe environment.  

### **Platform Challenges**  
- **SQL Injection**  
- **Cross-Site Scripting (XSS)**  
- **File Upload Vulnerabilities**  
- **Weak Password Validation**  
- **Admin Login Exploitation**  

HackTrek also includes a **Chatbot** implemented directly within the MERN stack to guide users through challenges.  

---

## **Prerequisites**  
Before setting up HackTrek, ensure the following are installed on your system:  
- **Node.js** (v14 or later)  
- **MongoDB** (Local or cloud-based)  
- **npm** (Node Package Manager)  
- **Git** (for cloning the repository)  

---

## **Code Dependencies**  
### **Backend:**  
- **bcryptjs:** For password hashing.  
- **jsonwebtoken:** To create and verify tokens for authentication.  
- **xss:** To handle XSS sanitization in vulnerable endpoints.  
- **multer:** For managing file uploads in challenges.  
- **dotenv:** To manage environment variables.  
- **body-parser:** To parse incoming request bodies in a middleware.  

### **Frontend:**  
- **axios:** To handle API requests.  
- **react-router-dom:** For routing in the frontend.  
- **Bootstrap:** For UI components and styling.  

> For a complete list of dependencies, refer to the `package.json` files in both the **backend** and **frontend** directories.

---

## **Setup Instructions**  

### **Clone the Repository**  
```bash
git clone https://github.com/Balwanth-stark/HackTrek.git
cd HackTrek
```

### **Backend Setup**  
1. Navigate to the **backend** directory:  
   ```bash
   cd backend
   ```
2. Install the necessary dependencies:  
   ```bash
   npm install
   ```
3. Create a `.env` file in the **backend** directory with the following variables:  
   ```plaintext
   MONGO_URI=<your_mongo_connection_string>
   PORT=5000
   ```
4. Create an `uploads` folder to store files uploaded during challenges:  
   ```bash
   mkdir uploads
   ```
5. Start the backend server:  
   ```bash
   npm start
   ```

### **Frontend Setup**  
1. Navigate to the **frontend** directory:  
   ```bash
   cd ../frontend
   ```
2. Install the necessary dependencies:  
   ```bash
   npm install
   ```
3. Start the frontend server:  
   ```bash
   npm start
   ```

---

## **Features**  

### **Challenges**  
- **SQL Injection:** Exploit database queries to bypass authentication.  
- **XSS (Reflected and DOM-based):** Inject scripts and manipulate the DOM.  
- **File Upload Vulnerabilities:** Test file upload restrictions and exploit them.  
- **Admin Login Exploitation:** Gain unauthorized access through improper validation.  
- **Weak Password Validation:** Discover and exploit weak password mechanisms.  

### **Chatbot Assistant**  
The chatbot is implemented within the MERN stack and offers:  
- Guidance for solving challenges.  
- Educational insights and solutions.  

---

## **Contribution**  
We welcome contributions to improve the platform and suggestions for new challenges. If you encounter any issues, please submit them via **GitHub Issues**.

---

## **License**  
This project is licensed under the **MIT License**. See the `LICENSE` file for more details.  

---

## **Happy Hacking!** 🛡️✨  
