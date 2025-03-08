# 🚀 Bank Management App
Simple CRUD API using **Spring Boot**, **Spring Data JPA**, and **MySQL**.  

## 🛠 Technologies Used  
- ⚡ Spring Boot  
- 📦 Spring Data JPA  
- 🗄️ MySQL  
- 📡 Postman  

## 🔗 API Endpoints  
| 🔹 Method | 🔹 Endpoint | 🔹 Description |
|-----------|-----------|----------------|
| **🟢 GET** | `/accounts` | Get all bank accounts |
| **🟢 GET** | `/accounts/{id}` | Get bank account by ID |
| **🟠 POST** | `/accounts/add` | Create a new bank account |
| **🔵 PUT** | `/accounts/update/{id}` | Update bank account details |
| **🔵 PUT** | `/accounts/{id}/deposit` | Deposit money into an account |
| **🔵 PUT** | `/accounts/{id}/withdraw` | Withdraw money from an account |
| **🔴 DELETE** | `/accounts/delete/{id}` | Close/Delete a bank account |

## ⚙️ Setup Instructions  
### 📥 Clone the repository:  
```bash
git clone https://github.com/your-repo-url.git
cd your-project-folder
```  

### 🛠 Configure `application.properties`:  
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_database
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```  

### 🚀 Run the application:  
```bash
mvn spring-boot:run
```  

✅ Test the API using **Postman** or any API testing tool.  

💡 This project serves as a basic template for building **RESTful APIs** with **Spring Boot**.

