Smart Task Manager (Java + SQLite)

This is a console task manager built in Java 17 and SQLite. It uses OOP, the DAO pattern, and a clean project structure. You can add tasks, view tasks, update tasks, mark tasks complete, and delete tasks.

Tech Stack:
	•	Java 17+
	•	Maven
	•	SQLite (Xerial JDBC driver)
	•	DAO pattern
	•	Singleton database manager

Project Structure:
smart-task-manager/
src/main/java/com/taskmanager/Task.java
src/main/java/com/taskmanager/DatabaseManager.java
src/main/java/com/taskmanager/TaskDao.java
src/main/java/com/taskmanager/TaskManagerApp.java
pom.xml
.gitignore
README.md

How to Run:

Requirements:
	•	JDK 17 or higher
	•	Maven

Steps:
	1.	Clone the project:
git clone https://github.com/moistr203/smart-task-manager.git
cd smart-task-manager
	2.	Build the project:
mvn clean package
	3.	Run the application:
java -jar target/smart-task-manager-1.0.0-jar-with-dependencies.jar

A SQLite database file named task_manager.db will be created the first time the app runs.

Features:
	•	Add a task
	•	View all tasks
	•	Update a task
	•	Mark a task complete
	•	Delete a task

Notes:
	•	The app stores data in a local SQLite database file
	•	Data is saved between runs
	•	Demonstrates clean OOP and DAO structure
