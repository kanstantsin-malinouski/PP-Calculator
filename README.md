# Console Calculator (C#)

A tiny, interactive calculator for the terminal. Supports addition, subtraction, multiplication, and division with input validation and graceful error handling.

## 🚀 Features

- Interactive prompt for two numbers and an operator
- Supports add, subtract, multiply, divide
- Validates numeric input; protects against division by zero
- Friendly loop until you choose to exit

## ⚙️ Technologies Used
- **Language:** C#  
- **Framework:** .NET 8.0 — Microsoft.NETCore.App 
- **Runtime type:** Console Application  
- **Tools:** .NET SDK

## 🧠 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/kanstantsin-malinouski/PP-Calculator.git
cd PP-Calculator
```

### 2. Run the Project
```bash
dotnet run
```


## 💻 Example Session

```
Console Calculator in C#
------------------------

Type a number, and then press Enter: 12.5
Type another number, and then press Enter: 3
Choose an operator from the following list:
    a - Add
    s - Subtract
    m - Multiply
    d - Divide
Your option? m
Your result: 37.5

Press 'n' and Enter to close the app, or press any other key and Enter to continue: n
```


## 🏗️ Project Structure

```
Calculator/
├── Program.cs               # Contains Calculator class + Program entry point
└── ConsoleCalculator.csproj # Targets Microsoft.NETCore.App runtime
```


## 📜 License

This project is open-sourced for educational purposes.
