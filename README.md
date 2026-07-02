# 🗳️ C++ Voting System

A console-based **Electronic Voting System** developed in **C++** that simulates a real-world voting process. The application allows voters to cast votes using their CNIC, automatically identifies their constituency, prevents duplicate voting, and provides an admin panel for managing candidates and election results.

---

## 📌 Features

- 🗳️ Secure vote casting
- 🪪 CNIC-based voter verification
- 📍 Automatic constituency detection
- 🚫 Duplicate vote prevention
- 👨‍💼 Admin login system
- ➕ Add new candidates
- ❌ Remove existing candidates
- 📊 View election results
- 🏛️ View candidates by constituency
- 🔄 Reset all votes
- 💾 Automatic file handling
- 📋 Persistent vote storage
- 🧩 Object-Oriented Programming (OOP)

---

## 🛠️ Technologies Used

- C++
- Object-Oriented Programming (OOP)
- File Handling
- Templates
- Arrays
- Inheritance
- Console I/O

---

## 📁 Project Structure

```
Voting-System/
│
├── main.cpp
└── README.md
```

> **Note:** The program automatically creates **`candidates.txt`** and **`voted.txt`** the first time it is executed. No manual setup is required.

---

## 📄 Automatically Generated Files

### `candidates.txt`

Stores candidate information in the following format:

```
Candidate Name|Constituency|Votes
```

Example:

```
Shahbaz Sharif|NA-52|0
Maryam Nawaz|NA-52|0
Imran Khan|NA-53|0
```

---

### `voted.txt`

Stores the CNIC numbers of voters who have already cast their vote to prevent duplicate voting.

Example:

```
3521234567890
3539876543210
```

---

## 🏛️ Supported Constituencies

| CNIC Prefix | Constituency |
|-------------|--------------|
| 352 | NA-52 |
| 353 | NA-53 |
| 354 | NA-54 |
| 355 | NA-55 |
| 356 | NA-56 |

The first three digits of a voter's CNIC determine their constituency.

---

## 🔑 Admin Features

The administrator can:

- Add candidates
- Remove candidates
- View all candidates and results
- View candidates by constituency
- Reset all votes
- Clear voting history

**Default Admin Password**

```
admin123
```

---

## 🗳️ Voting Process

1. Enter a valid 13-digit CNIC.
2. The system determines the voter's constituency.
3. Candidates for that constituency are displayed.
4. Select a candidate.
5. The vote is recorded.
6. The CNIC is saved to prevent duplicate voting.

---

## ▶️ How to Run

### Compile

```bash
g++ main.cpp -o VotingSystem
```

### Run

**Windows**

```bash
VotingSystem.exe
```

**Linux/macOS**

```bash
./VotingSystem
```

---

## 📚 OOP Concepts Used

- Classes & Objects
- Inheritance
- Constructors
- Templates
- Encapsulation
- Arrays
- Functions
- File Handling

---

## 📜 License

This project was developed for educational purposes and is free to use, modify, and learn from.
