📋 Table of Contents
✨ Overview
🚀 Features
🛠️ Technologies Used
📦 Setup and Installation
📖 Usage
📂 Directory Structure

✨ Overview
The DisplayAllProduct servlet is a foundational Java project designed to demonstrate the integration of servlets, JSP, and a MySQL database.
It retrieves product data from a database and forwards it to a JSP page for rendering. Ideal for those learning Java web development.

🚀 Features
🗂️ Fetches data seamlessly from a MySQL database.
🌐 Displays data dynamically on a JSP page.
📋 Modular and reusable code structure.
✅ Implements HTTP request handling with servlets.

🛠️ Technologies Used
Language: Java
Database: MySQL
Web Framework: Servlet API
Frontend: JSP (JavaServer Pages)
Server: Apache Tomcat
Dependency Management: Maven (optional)

📦 Setup and Installation
Prerequisites
Ensure the following tools are installed on your system:

🖥️ Java JDK 8+
🐱‍💻 Apache Tomcat 9+
🐬 MySQL Server
🛠️ IDE (e.g., Eclipse, IntelliJ IDEA)

📖 Usage
Navigate to the URL provided after deployment.
View all products in a table rendered by the display.jsp page.
Extend the functionality to include filtering, sorting, or additional views as needed.

📂 Directory Structure
├── src/main/java/com/tka
│   ├── DisplayAllProduct.java
│   ├──AddProduct.java
│   ├──Product.java
├── src/main/webapp
│   ├── display.jsp
│   ├──add.jsp
│   ├──index.jsp
│   ├── WEB-INF/web.xml

