# Reservoom (Hotel Reservation System)

A clean, MVVM-based WPF desktop application for managing room reservations.  
Built using **C#**, **WPF**, and **Entity Framework**, this project demonstrates strong architectural practices with MVVM, command binding, view state management, and async operations.

---

## 🧠 Features

- 🏠 View available rooms and reservations
- ➕ Create and manage new reservations
- 🔁 Navigate between pages using command-based logic
- 💾 Optional: Save data using EF Core or an in-memory database
- 💡 Clear separation of concerns using the MVVM pattern

---

## 🧱 Technologies Used

- **C# / .NET**
- **WPF (Windows Presentation Foundation)**
- **MVVM (Model-View-ViewModel)**
- **ICommand / AsyncCommand**
- **Visual Studio 2022**
- **Entity Framework Core**

---

## 📂 Folder Structure

Reservoom/
│
├── Commands/ # Custom command logic (navigation, async)
├── Services/ # Business logic services
├── Stores/ # App-wide state stores (e.g., user, reservations)
├── ViewModels/ # View-specific binding logic
├── Views/ # XAML-based user interfaces
├── Models/ # Data models (Room, Reservation)
├── DbContexts/ # Entity Framework Core DB context
├── DTOs/ # Data transfer objects
├── Converters/ # UI converters (e.g., BooleanToVisibility)
└── Exceptions/ # Custom exception handling


## 📌 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/reservoom.git
2. Open the .sln file in Visual Studio 2022
3. Build and run the project

## 🙋‍♂️ Author

**Ayush Gupta**  
- [LinkedIn](https://www.linkedin.com/in/ayush-gupta-34694b146)
