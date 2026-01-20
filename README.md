# Hotel Management System

# 🚀 Installation & Setup

## 1. Install Softwares<br>
-Node.js (v14 or higher)<br>
-MySQL (v8.0 or higher)<br>
-npm -ensure node and npm are available on the command line

## 2. Install Dependencies<br>
 -Run all commands in sequence inside vscode terminal<br>
```bash
-Inside root folder run
npm install
-go inside server directory
cd server
-Install server dependencies
npm install
-Exit server directory and go to client directory
cd ../client
-Install client dependencies
npm install
```

## 3. Database Setup<br>
1.Open the MySQL Command Line Client<br>
2.Enter your mysql password 3- Run the following commands<br>
```bash
SOURCE C:\path\to\your\project\server\with\these\inverted\slashes\database.sql;
```
## 4. Environment Configuration<br>
Create a .env file in the server directory:<br>
-change DB_PASSWORD to your pc's mysql password
```bash
PORT=5000
DB_HOST=localhost
DB_USER=root<
DB_PASSWORD=your-pcs-mysql-password
DB_NAME=hotel_management
JWT_SECRET=your-super-secret-jwt-key
```

## 5. Run the Application<br>
```bash
# run them separately on two terminals:
# Backend (from root)
npm run server
# Frontend (from root)
npm run client
```

