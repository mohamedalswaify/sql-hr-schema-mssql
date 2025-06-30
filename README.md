
# 🗃️ HR Schema - SQL Server Edition

This repository contains a full SQL script to **create and populate** the classic **Human Resources (HR)** schema using **Microsoft SQL Server**. The script includes both **DDL** (structure) and **DML** (data) commands — all in one file.

---

## 📄 Script Name

```bash
hr-schema-mssql.sql
```

This single script:
- 🔧 Creates all required tables  
- 🧩 Defines relationships (foreign keys)  
- 💾 Inserts sample data for practice and learning  

---

## 🧪 How to Use

### ✅ Requirements:

- 🧱 **SQL Server 2019 or newer**  
  🔗 [Download SQL Server 2019 (Developer Edition - Free)](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

- 💻 **SQL Server Management Studio (SSMS)**  
  🔗 [Download SSMS](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)

---

### ⚙️ Steps to Run:

1. **Open SQL Server Management Studio (SSMS)**  
2. Connect to your server and **create a new database**, e.g.:
   ```sql
   CREATE DATABASE HR;
   GO
   USE HR;
   ```

3. **Open** the file `hr-schema-mssql.sql` inside SSMS  
4. **Execute** the script by clicking ▶️ or pressing `F5`  
5. ✅ Done! Your HR schema is now created and populated with sample data.

---

## 📋 Schema Overview

The following tables will be created:

| Table         | Description                 |
|---------------|-----------------------------|
| `regions`     | List of global regions       |
| `countries`   | Countries linked to regions  |
| `locations`   | Physical office addresses    |
| `departments` | Company departments          |
| `jobs`        | Available job roles          |
| `employees`   | Employees working in company |

---

## 👤 Author

- 👨‍🏫 **Mohamed Alswaify**
- 📱 Phone: +966-564842804
- 🌐 GitHub: [github.com/mohamedalswaify](https://github.com/mohamedalswaify)
- 🔗 LinkedIn: [linkedin.com/in/mohamedalswaify](https://www.linkedin.com/in/mohamedalswaify)
- 💬 WhatsApp: [Chat on WhatsApp](https://wa.me/966564842804)
-----

## 📌 Notes

- Script is fully tested on SQL Server
- Ideal for beginners and bootcamp practice
- Clean formatting and comments for educational use

---

## 📌 License

Free to use for educational and training purposes. Attribution appreciated.


🎓 **Happy SQL-ing!**
