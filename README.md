Career Calculator 🎯

A Java application that recommends a suitable career path based on a user's skills and interests. It matches user input against a MySQL-backed database of skill/interest/career combinations to suggest a fitting career.

✨ Features

Takes a user's skill and interest as input
Matches input against a database of career mappings (e.g. Programming + AI → Machine Learning Engineer)
Returns a recommended career path
Backed by MySQL for storing and querying career data


🛠️ Tech Stack

Language: Java
Database: MySQL (JDBC via mysql-connector)
IDE: IntelliJ IDEA

📁 Project Structure

CareerCalculator/
├── src/              # Java source files
├── frontend/         # UI files
├── careerdb.sql      # Database schema + sample career data
├── update_data.sql   # Additional data updates
└── mysql-connector.jar

🚀 Getting Started

Prerequisites
JDK 8 or above
MySQL Server
An IDE such as IntelliJ IDEA


Setup
Clone the repository
bash   git clone https://github.com/ibrahimx-dev/CareerCalculator.git


Set up the database
Run careerdb.sql in your MySQL client to create the database and seed sample career data
Run update_data.sql if additional data updates are needed

Configure the database connection
Update the database URL, username, and password in your Java source file (wherever the JDBC connection is established)

Run the project
Open the project in IntelliJ IDEA and run the main class

🔮 Future Improvements
Expand the career database with more skill/interest combinations
Add a proper web or GUI interface
Move database credentials to a config file instead of hardcoding

📄 License
This project is open source. Feel free to use and modify it.
