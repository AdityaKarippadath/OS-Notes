# Operating Systems for SDE Interview Preparation

A comprehensive **Operating Systems Interview Handbook** designed for Software Development Engineers preparing for top tech companies such as Amazon, Google, Microsoft, Meta, Uber, and others.

This project is written entirely in **LaTeX** and structured to generate a **600–800+ page technical book** covering theory, numericals, interview questions, and system design applications of Operating Systems.

---

## 📘 Book Overview

This handbook focuses on:

- Core Operating Systems concepts
- Interview-relevant explanations (FAANG level)
- Numerical problem solving
- Linux internals
- Modern concurrency and distributed systems
- System design connections
- Revision and cheat sheets

It is designed as a **complete end-to-end preparation resource** for OS interviews.

---

## 📂 Project Structure

```

os-handbook/
│
├── main.tex                # Main LaTeX entry point
├── preamble.tex           # Packages, styles, environments
├── references.bib         # Bibliography (optional)
├── README.md
│
├── frontmatter/
│   └── title.tex
│
├── chapters/
│   ├── part1_fundamentals/
│   ├── part2_processes_threads/
│   ├── part3_synchronization/
│   ├── part4_deadlocks/
│   ├── part5_memory_management/
│   ├── part6_file_systems/
│   ├── part7_io/
│   ├── part8_modern_os/
│   ├── part9_system_design/
│   └── part10_interview_mastery/
│
├── images/                # Chapter-wise diagrams
├── diagrams/              # Source diagrams (drawio, svg)
├── code/                  # Code examples (C/C++/Java/Python)
└── tables/                # Reusable LaTeX tables

````

---

## 🧠 Topics Covered

### Part 1: Fundamentals
- OS Introduction
- Computer Architecture

### Part 2: Processes & Threads
- Processes
- Threads
- CPU Scheduling

### Part 3: Synchronization
- Critical Section Problem
- Mutex, Semaphore, Monitors
- Classical Problems

### Part 4: Deadlocks
- Deadlock Conditions
- Banker's Algorithm
- Detection & Recovery

### Part 5: Memory Management
- Paging
- Segmentation
- Virtual Memory
- Page Replacement Algorithms

### Part 6: File Systems
- File System Design
- Inodes
- Disk Scheduling

### Part 7: I/O Systems
- I/O Models
- Drivers and Controllers
- epoll, select, poll

### Part 8: Modern OS
- Linux Internals
- Containers & Virtualization
- OS Security

### Part 9: System Design Link
- High Concurrency Systems
- Performance Optimization
- Distributed Systems OS Concepts

### Part 10: Interview Mastery
- 150+ Interview Questions
- 100+ Numerical Problems
- Cheat Sheets
- Revision Notes

---

## ⚙️ How to Build the PDF

### Option 1: Using LaTeX locally

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
````

### Option 2: Using Makefile

```bash
make
```

---

## 🧱 Requirements

Install a full LaTeX distribution:

### Ubuntu

```bash
sudo apt install texlive-full
```

### macOS

```bash
brew install --cask mactex
```

### Windows

Install MiKTeX:
[https://miktex.org/](https://miktex.org/)

---

## 🧩 Design Philosophy

This book is designed with:

* Interview-first explanations
* Minimal theory overload
* Heavy focus on:

  * Diagrams
  * Comparisons
  * Numericals
  * Real-world system mapping
* FAANG interview patterns

---

## 🎯 Target Audience

* SDE-1 / SDE-2 candidates
* Backend engineers
* System design learners
* CS students preparing for placements
* Competitive programming + interview candidates

---

## 📌 Key Features

* 600–800 page structured handbook
* FAANG-focused OS coverage
* Numerical problem workbook
* Cheat sheet revision system
* System design integration
* Linux internals deep dive

---

## 📚 Output Structure

Each chapter includes:

* Concept explanations
* Diagrams (TikZ)
* Code examples
* Interview questions
* MCQs
* Cheat sheet
* Revision notes

---

## 🚀 Future Improvements

Planned enhancements:

* Add Kubernetes deep dive section
* Add OS debugging scenarios
* Add real interview transcripts
* Add performance tuning case studies

---

## 👤 Author

**Aditya Udai**

---

## 📄 License

For educational and personal interview preparation use.

---

## ⭐ If you like this project

Consider extending it with:

* Distributed Systems Handbook
* System Design Handbook
* Database Internals Handbook


