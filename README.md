
# System Gym

**System Gym** is a desktop-based Java application designed to manage gym memberships and operations. It provides a simple, user-friendly interface for gym staff to register new members, view and manage existing ones, handle login/authentication, and maintain records in an efficient and organized manner.

## 📌 Features

- 🧾 **Member Registration**: Easily add new gym members with personal details.
- 🔐 **Secure Login**: Authentication system for secure access.
- 👤 **View Members**: Access detailed member information.
- 📁 **Membership Plans**: Support for different gym subscription types.
- 🔄 **Password Recovery**: Recover forgotten passwords securely.
- 📊 **Simple Interface**: GUI built using Java Swing for ease of use.

## 🛠️ Technologies Used

- **Java SE**
- **Java Swing** for GUI
- **NetBeans IDE Project Structure**
- **JDBC** for database connectivity
- **MySQL** or compatible relational database (configurable)

## 🖥️ How to Run

1. **Clone or Download** the project:

   ```bash
   https://github.com/MazenWahed22/GymSystem.git
   ```

2. **Open in NetBeans** or any Java IDE that supports Ant builds.

3. **Set up the database**:
   - Create a MySQL database.
   - Execute the required SQL tables (not included in this version; you may need to derive it from `ConnectionProvider.java`).
   - Configure the connection inside `ConnectionProvider.java` with your DB credentials.

4. **Build and Run** the project using your IDE or with:

   ```bash
   ant run
   ```

## 📂 Project Structure

```
System_Gym/
├── src/
│   ├── Add_Member.java
│   ├── LOGIN.java
│   ├── Main_INTERFACE.java
│   ├── Register.java
│   ├── Restore_Pass.java
│   ├── viiew_member.java
│   └── Project/ConnectionProvider.java
├── nbproject/          # NetBeans project files
├── build.xml           # Ant build file
└── manifest.mf         # Manifest configuration
```

## ⚠️ Requirements

- Java Development Kit (JDK) 8 or higher
- MySQL Server (or compatible)
- NetBeans IDE (recommended for smooth import)
- Apache Ant (optional for command-line builds)

## ✅ Usage

- Login using provided admin credentials.
- Add or view members through the main interface.
- Manage password resets as needed.

## 📄 License

This project is open-source and available under the MIT License.

---

**Developed with care for efficient gym management.**
