# Simple Go Calculator
A beginner-friendly calculator program written in **Go**, containerized using **Docker**.

---

## Project Description
This is a simple command-line calculator that takes two numbers and an operator (`+`, `-`, `*`, `/`) from the user and prints the result.  
It handles basic validation (like division by zero) and is ideal for learning **Go** and **Docker fundamentals**.

---

## 📁 Project Structure
```
.
├── main.go        # Go source code (calculator logic)
├── Dockerfile     # Docker instructions to build and run the app
└── README.md      # Project documentation
```

---

## How to Run the App

### ▶ Run Locally (without Docker)
Make sure Go is installed, then run:
```bash
go run main.go
```

---

### 🐳 Run with Docker

1. **Build the image:**
   ```bash
   docker build -t mahmoudelqalini/simple-go-calculator:latest .
   ```

2. **Run the container:**
   ```bash
   docker run -it mahmoudelqalini/simple-go-calculator
   ```

---

## Example Output
```
Simple Go Calculator
------------------------
Enter first number: 10
Enter operator (+, -, *, /): *
Enter second number: 3
Result: 30.00
```

---

## 🌐 Docker Hub
The image is publicly available on Docker Hub:  
👉 [https://hub.docker.com/r/mahmoudelqalini/simple-go-calculator]

---

## Technologies Used
- **Go** (Golang)
- **Docker**

---
