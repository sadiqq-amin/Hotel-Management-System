# Hotel Management System

# 🚀 Installation & Setup

## 1. Install Softwares<br>
-Node.js (v14 or higher)<br>
-MySQL (v8.0 or higher)<br>
-npm -ensure node and npm are available on the command line

## 2. Install Dependencies<br>
- Run all commands in sequence inside vscode terminal<br>
-Inside root folder run<br>
npm install<br>
-go inside server directory<br>
cd server<br>
-Install server dependencies<br>
npm install<br>
-Exit server directory and go to client directory
cd ../client<br>
-Install client dependencies
npm install

## 3. Database Setup3<br>
1.Open the MySQL Command Line Client<br>
2.Enter your mysql password 3- Run the following commands<br>
SOURCE C:\path\to\your\project\server\with\these\inverted\slashes\database.sql;

## 4. Environment Configuration<br>
Create a .env file in the server directory:<br>
-change DB_PASSWORD to your pc's mysql password<br>
PORT=5000<br>
DB_HOST=localhost<br>
DB_USER=root<br>
DB_PASSWORD=your-pcs-mysql-password<br>
DB_NAME=hotel_management<br>
JWT_SECRET=your-super-secret-jwt-key<br>

## 5. Run the Application<br>
run them separately on two terminals:br>
Backend (from root)<br>
npm run server<br>
Frontend (from root)<br>
npm run client


