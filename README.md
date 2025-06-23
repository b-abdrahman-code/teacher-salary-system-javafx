A desktop application for managing and calculating teacher salaries, built with **JavaFX** and **MySQL**. It allows secure login, dynamic salary calculation based on input parameters, and persistent storage via database and configuration files.

---

## 📌 Features

- 🔐 **User Authentication**  
  Secure login using stored credentials in the database.

- ⚙️ **Database Configuration**  
  - Configurable MySQL connection (user, password, port).
  - Stores settings in a `.properties` file for reuse.

- 🧮 **Salary Calculation**  
  - Inputs: P₀, i, T₀, Tₓ, D, R, Qj, Pf, Qm (m³/h), Qp (L/s).
  - Real-time calculation logic handled by a separate class.

- 🖥️ **JavaFX UI**  
  - Transparent stage with close button on all pages.
  - Supports RTL layout for Arabic users.
  - Optional app icon integration.

- 🗃️ **Data Persistence**  
  - Settings saved and loaded from file.
  - Salary results optionally stored in the database.

---

## 🏗️ Tech Stack

| Layer        | Technology     |
|--------------|----------------|
| UI           | JavaFX         |
| Backend      | Java           |
| Database     | MySQL          |
| Config Files | `.properties`  |
| IDE          | IntelliJ IDEA  |

---

## 📂notes:

this project is messy and dont blame me for not using the best practices i had 2 weeks to finish this ...ehhh FOR the database i wont brother to add it here ..if u find it in the project its urs buddy(just look for it) ..honestly bothering to learn javafx its kinda pointless..DON'T.. maven architecture is hard to deal with ..anyway ... thats it
