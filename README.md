# 🚀 Capstone-Portal
The Capstone Project Management System (CPMS) is a web-based platform designed to streamline the management, tracking, and evaluation of capstone projects for students, guides, and coordinators. It centralizes project-related activities, enhances communication, and ensures efficient workflow management.


# 🛠️ Project Setup
Follow these instructions to setup and run the project on your local machine.

# Frontend Setup(React.js)
1. Navigate to the frontend directory:

    ```bash
    cd frontend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Start the development server:

    ```bash
    npm run dev
    ```
4. Access the frontend at:

   ```bash
   http://localhost:5173
   ```
# Backend Setup(Spring Boot)
1. Navigate to the backend directory:

   ```bash
   cd backend
   ```

2. Update the database credentials in application.properties:
   - Set your **username** and **password** for the database.
   - Create the required database.

3. Provide your Gmail and app password for email functionality.

4. Build the project:

   ```bash
   ./mvnw clean install   # For Linux/Mac
   mvnw.cmd clean install # For Windows
   ```

5. Start the Spring Boot server:

   ```bash
   ./mvnw spring-boot:run   # For Linux/Mac
   mvnw.cmd spring-boot:run # For Windows
   ```

6. Access the backend server at:

   ```bash
   http://localhost:5173/
   ```

# 📂 Project Structure
<pre><code>```bash Capstone-Portal/ 
      ├── frontend/ # React.js frontend 
      │ ├── src/ # Source code 
      │ ├── public/ # Static files 
      │ └── package.json # Project config 
      ├── backend/ # Spring Boot backend 
      │ ├── src/ # Source code 
      │ └── pom.xml # Maven configuration 
      └── README.md # Project documentation```</code></pre>


# ⚙️ Technologies Used
Frontend:
- React.js
- HTML, CSS, JavaScript
- Axios for API communication
  
Backend:
- Spring Boot
- Java
- Maven
  
Tools:
- Visual Studio Code / IntelliJ IDEA
- Postman for API testing

# 🌟 Contributing
Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature/YourFeatureName
   ```
   
3. Make your changes and commit:

   ```bash
   git commit -m "Add YourFeatureName"
   ```

4. Push the changes:

   ```bash
   git push origin feature/YourFeatureName
   ```

5. Open a Pull Request.

# 📧 Contact 
- Developer:[Feni Bhuva](https://example.com)

- Github:[@Feni16](https://example.com)

# Thank You!
Thank you for checking out Capstone-Portal! If you find it useful, don’t forget to ⭐ the repository.

