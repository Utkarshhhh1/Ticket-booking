# 🚂 Railway Ticket Booking System

A console-based application built with Java that simulates a railway ticket booking system (similar to IRCTC). It allows users to search for trains, book tickets, and manage their bookings using a local JSON database.

## ✨ Features
* **User Authentication:** Register and login securely.
* **Search Trains:** Find trains between source and destination stations.
* **Book Tickets:** Select seats and book tickets instantly.
* **Cancel Tickets:** Cancel existing bookings.
* **Data Persistence:** Uses local JSON files (`users.json` and `trains.json`) to save data so it isn't lost when the app closes.

## 🛠️ Tech Stack
* **Language:** Java
* **Build Tool:** Gradle
* **Database:** JSON (File Handling)
* **IDE:** IntelliJ IDEA

## 🚀 How to Run locally

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/Utkarshhhh1/Ticket-booking.git](https://github.com/Utkarshhhh1/Ticket-booking.git)
    ```

2.  **Navigate to the project directory**
    ```bash
    cd Ticket-booking
    ```

3.  **Build the project**
    ```bash
    ./gradlew build
    ```

4.  **Run the application**
    ```bash
    ./gradlew run
    ```
    *(Or simply open the project in IntelliJ IDEA and run `App.java`)*

## 📂 Project Structure
* `src/main/java/org/example/entities`: Contains core classes like `User`, `Train`, and `Ticket`.
* `src/main/java/org/example/services`: Contains logic for bookings and train management.
* `src/main/java/org/example/localDb`: Stores the JSON database files.

## 🔮 Future Improvements
* Add admin functionality to add/remove trains.
* Implement a Graphical User Interface (GUI).
* Switch from JSON to a real database like MySQL or MongoDB.

---
*Created by [Utkarshhhh1](https://github.com/Utkarshhhh1)*
