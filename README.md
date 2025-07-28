# 🤖 Robot Arm Controller

## About
This project is a web-based control panel for a 6-motor robotic arm built using:
- **HTML** – for the user interface
- **PHP** – for backend processing
- **MySQL** – to store servo positions (poses)

The interface allows users to:
- Control 6 motors using sliders
- Save motor positions (poses) to the database
- View & Run the latest pose

---

## 📁 Files

| File Name       | Description |
|-----------------|-------------|
| `index.html`    | Main control panel UI |
| `web2.php`      | PHP script to save motor positions to the database |
| `db.php`        | Database connection file |
| `README.md`     | Project documentation |

---

## 🧠 How it works

1. User adjusts motor sliders.
2. Clicks "Save Pose".
3. The values are sent via POST to `web2.php`.
4. PHP inserts values into the `poses` table in MySQL.
5. (Optional) Another script can fetch and run the latest pose.

