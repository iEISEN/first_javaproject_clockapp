# ⏰ Java Clock App  

This is my **CSE 1116 – Object Oriented Programming Laboratory Project**, completed during the **Summer 222 Trimester** in my **first year at United International University (UIU)**.  
It was my **first Java application**, a simple yet functional **Clock App** that displays the real-time system time and includes multiple timing utilities like **Stopwatch**, **Alarm**, **Timer**, and **Counter**.

---

## 🕒 Project Overview  

The **Clock App** is built using **Java Swing and AWT**, demonstrating the use of **Object-Oriented Programming concepts** such as classes, inheritance, and threads.  
The main clock updates continuously in real time by fetching the system time using a dedicated **thread**. The application also offers additional features that enhance its functionality and interactivity.

---

## 🚀 Features  

- 🕓 **Real-Time Clock** – Displays accurate system time (hours, minutes, seconds).  
- ⏱️ **Stopwatch** – Start, stop, and reset functionality for time tracking.  
- ⏰ **Alarm System** – Allows users to set alarms with alert sound.  
- ⏳ **Timer** – Countdown timer with custom input time.  
- 🔢 **Counter** – Simple number counter with increment and reset options.  
- 🌈 **Modern UI** – Clean interface with a nice background for better visual appeal.  

---

## 🛠️ Technologies Used  

- **Language:** Java  
- **GUI Frameworks:** Swing, AWT  
- **IDE:** NetBeans (originally built), also runnable in IntelliJ IDEA  
- **Concepts Used:**  
  - Object-Oriented Programming (OOP)  
  - Multithreading  
  - Event Handling  
  - GUI Design with Swing Components  

---

## ⚙️ How It Works  

1. The main `Clock` class creates a GUI frame using `JFrame`.  
2. A **thread** runs in the background to fetch the current system time every second.  
3. The GUI updates dynamically to show the current time.  
4. The Stopwatch, Timer, and Alarm functionalities use separate threads to manage timing operations independently.  

---

## 💻 How to Run  

1. Clone or download the repository.  
2. Open it in **IntelliJ IDEA** or **NetBeans**.  
3. Compile and run the main class:
   ```bash
   javac Main_frame.java
   java Main_frame
