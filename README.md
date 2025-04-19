# 💰 MyWallet - Fullstack Expense Tracker

**MyWallet** is a robust and intuitive **full-stack expense tracking web application** that helps users efficiently manage their day-to-day finances. Built using **Spring Boot, React.js, and MySQL**, it offers features like **role-based authentication**, **transaction management**, **budgets**, and **financial summaries**, providing both users and administrators a secure and seamless experience.

---

## ✨ Features

### 👤 **Authentication & Authorization**
- Secure **sign-up / sign-in** with JWT-based authentication
- **Email verification** and **password reset** support
- **Role-based access**: separate dashboards and privileges for users and admins

### 📊 **User Dashboard**
- Track **expenses and income** by category
- View **monthly summaries** and **spending statistics**
- Manage **recurring/upcoming transactions**
- **Budget planning** and category-wise insights

### 🔧 **Admin Capabilities**
- Full **CRUD access** to manage users, categories, and transactions
- Advanced **search**, **filtering**, and **pagination** for better control
- View all user activities and analytics

---

## 🛠️ Tech Stack

- 🔙 **Backend**: Spring Boot, Spring Security, Spring Data JPA, JWT
- 🌐 **Frontend**: React.js, CSS, Axios
- 🛢️ **Database**: MySQL
- 📧 **Email Service**: JavaMailSender (SMTP)

---

## 🚀 Getting Started

### 📦 Step 1: Fork & Clone the Repository

```bash
git clone https://github.com/amit-soham-16/MyWallet.git
cd Fullstack-Expense-Tracker
```
## ⚙️ Step 2: Backend Configuration
1.Update the following credentials in src/main/resources/application.properties:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/YOUR_DATABASE_NAME
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD

spring.mail.username=YOUR_EMAIL
spring.mail.password=YOUR_EMAIL_PASSWORD
```
## ▶️ Step 3: Run the Backend
- Start the Spring Boot application (ExpenseTrackerApplication.java)

- The application will auto-generate required tables.

- Insert seed data in categories table (e.g. expense/income types).

- To create an admin:

    -- Insert a user manually in users table with role set to admin.

## 💻 Step 4: Run the Frontend
```bash

cd ./frontend
npm install
npm start
```
Visit the app at http://localhost:3000
Start by creating a new user account and verify your email to access the app.






## 🖼️Screenshots


![Screenshot 2024-04-18 091743](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/dbcfdbd2-d515-4197-b5ff-11ba0aed2dcf)


Users's stuff

![Screenshot 2024-04-22 153501](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/a8e6d65b-626f-493e-922d-dd7c26d8294c)
![Screenshot 2024-04-22 153536](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/ed01d05e-cead-43c5-8959-6b64615fee43)
![Screenshot 2024-04-22 153556](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/40ab0b82-b38d-4a19-9044-d226e3f345ed)




Admin's stuff

![Screenshot 2024-04-18 092245](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/06454812-f542-4404-b9bf-e7d9b96b043d)
![Screenshot 2024-04-18 092306](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/a024fadc-5f6a-4e3f-96f6-f38dd1f6b477)

## 📌 Roadmap / Future Enhancements
- 💾 Export transaction data to PDF/CSV

- 📈 Charts and graphs for better data visualization

- 📱 Mobile responsive PWA version

- 🔔 Notifications for recurring expenses and budgets

- ☁️ Deployment on AWS/GCP with CI/CD

## 🤝 Contribution
Contributions are welcome! Please fork the repo, make your changes, and create a pull request.

## 👨‍💻 Author
- Amit Kumar
- 📫 amitk1602info@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/kumaramit02/) | [GitHub](https://github.com/amit-soham-16)



## 📜 License
This project is licensed under the MIT License.

## ⭐️ Show Your Support
If you like this project, give it a ⭐️ on GitHub! Contributions and suggestions are always welcome.


