# Monopoly Web (LAMP Stack)

A modern, browser-based remake of the classic board game **Monopoly**, built using the LAMP stack (Linux + Apache + MySQL + PHP).

## 🎮 Features
- User registration and login, allowing players to create and manage their account.  
- Persistent game saves: resume your Monopoly game any time.  
- Live leaderboard tracking player performance and rankings.  
- Complete web-based Monopoly gameplay: buying properties, collecting rent, trading with other players, and more.

## 🧠 Architecture & Technology
- Back-end: PHP with MySQL database for game logic, user and session management.  
- Front-end: HTML, CSS and JavaScript for interactive gameplay and UI.  
- Web server: Apache on Linux environment (LAMP).  
- Game state persistence and leaderboard maintained via MySQL data storage.

## 📷 Screenshot
[Main Page](https://raw.githubusercontent.com/USERNAME/REPO/BRANCH/path/to/image.png)
*The main game page with start-game options and user session info.*

## 🛠️ Getting Started / Installation
1. Clone the repository:  
   ```bash
   git clone https://github.com/andimatteo/Monopoly.git
2. Configure your LAMP environment (Linux + Apache + MySQL + PHP).
3. Import the SQL schema (file `dimatteo_641388.sql`) into a MySQL database.
4. Update the `config.php` (or the equivalent file) with your database credentials.
5. Point your web browser to the project’s root directory and register a new user to start playing.
