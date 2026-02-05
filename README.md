# 🎮 Number Guessing Game (Java + Maven)

## 📖 Project Description
Number Guessing Game is a simple console-based mini game developed using **Java and Maven**.  
The game generates a random number between **1 and 100**, and the player has to guess the number based on hints provided by the system.

---

## ⚙ Technologies Used
- Java  
- Maven  
- Command Line Interface  
- Executable JAR

---

## 🎯 Features
- Random number generation  
- User input through console  
- Hints: *Too High / Too Low*  
- Counts number of attempts  
- Maven-based project structure  
- Executable JAR file

---

## 🗂 Project Structure
```
GuessGame
│── pom.xml
│── .gitignore
│── target/GuessGame-1.0.jar
└── src/main/java/com/game/App.java
```

---

## ▶ How to Run the Game

### 1. Run Directly Using JAR
Open terminal in project folder and run:

```
java -jar target/GuessGame-1.0.jar
```

---

## 🛠 How to Build the Project

If you want to generate the JAR yourself:

```
mvn clean package
```

After build, the executable JAR will be created inside:

```
target/GuessGame-1.0.jar
```

---
