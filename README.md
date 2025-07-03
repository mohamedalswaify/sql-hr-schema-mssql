
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

### ✅ Requirements

#### 🖥️ For **Windows**:

* 🧱 **SQL Server 2022 (Developer Edition - Free)**
  🔗 [Download SQL Server 2022](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

* 💻 **SQL Server Management Studio (SSMS) 2022**
  🔗 [Download SSMS 2022](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)

* 📦 **SSMS - All Versions Archive**
  🔗 [Download SSMS (All Versions)](https://sqlserverbuilds.blogspot.com/2018/01/sql-server-management-studio-ssms.html)

---

#### 🍏 For **macOS** (via Docker):

* 🐳 **Install Docker**
  🔗 [Download Docker for Mac](https://www.docker.com/products/docker-desktop)

* 🧰 **Install Azure Data Studio**
  🔗 [Download Azure Data Studio](https://learn.microsoft.com/en-us/sql/azure-data-studio/download-azure-data-studio)

* ⚙️ **Run SQL Server inside Docker (Azure SQL Edge)**

  ```bash
  docker run -e "ACCEPT_EULA=1" -e "MSSQL_SA_PASSWORD=MohamedAlswaify@123" -e "MSSQL_PID=Developer" -e "MSSQL_USER=SA" -p 1433:1433 -d --name=sql mcr.microsoft.com/azure-sql-edge
  ```

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

| Table         | Description                        |
|---------------|------------------------------------|
| `regions`     | List of global regions             |
| `countries`   | Countries linked to regions        |
| `locations`   | Physical office addresses          |
| `departments` | Company departments                |
| `jobs`        | Available job roles                |
| `employees`   | Employees working in company       |
| `job_history` | History of employee job assignments|


## 👤 Author

* 👨‍🏫 **Mohamed Alswaify**
* 📱 **Phone:** +966-564842804
* 🌐 **Website:** [mohamed-alswaify.com](https://mohamed-alswaify.com/)
* 🔗 **GitHub:** [github.com/mohamedalswaify](https://github.com/mohamedalswaify)
* 💼 **LinkedIn:** [linkedin.com/in/mohamedalswaify](https://www.linkedin.com/in/mohamedalswaify)
* 💬 **WhatsApp:** [Chat on WhatsApp](https://wa.me/966564842804)
* 📘 **Facebook:** [facebook.com/Mohamed-Alswaify](https://www.facebook.com/people/Mohamed-Alswaify/61577335210627/?mibextid=wwXIfr&rdid=C0ubXhlMW0p2y1tA&share_url=https%3A%2F%2Fwww.facebook.com%2Fshare%2F1BvPMSn7Dc%2F%3Fmibextid%3DwwXIfr)


## 📌 Notes

- Script is fully tested on SQL Server
- Ideal for beginners and bootcamp practice
- Clean formatting and comments for educational use

---

## 📌 License

Free to use for educational and training purposes. Attribution appreciated.


🎓 **Happy SQL-ing!**
