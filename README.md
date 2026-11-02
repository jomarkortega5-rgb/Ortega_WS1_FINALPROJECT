DAILY HABIT AND STUDY TRACKER  (HTML5 + CSS3 + JavaScript + PHP + MySQL on XAMPP)

FILES
  index.html, style.css, script.js   front end (plain HTML/CSS/vanilla JavaScript, no libraries)
  api/db.php                         MySQL connection + helpers
  api/auth.php                       register, login (password_hash/password_verify), logout, session
  api/activities.php                 CRUD for activities
  database.sql                       tables: users, categories, activities

SETUP
  1. Install XAMPP and start Apache and MySQL in the XAMPP Control Panel.
  2. Copy this folder (named habit-tracker) into  C:\xampp\htdocs\
  3. Open http://localhost/phpmyadmin -> Import -> choose database.sql -> Go.
  4. Open http://localhost/Daily_habit_study_tracker/ in browser.
