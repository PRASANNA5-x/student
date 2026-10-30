# 🎓 Student Course Registration System

A browser-based **Student Course Registration System** built with pure HTML, CSS, and JavaScript — no backend or libraries needed.

## 📋 Features

- 👨‍🎓 **Add Students** — Register students with a unique Student ID and name
- 📚 **Create Courses** — Add courses with a unique Course ID, name, and seat capacity
- ✅ **Register Students** — Enrol a student in a course (capacity-controlled)
- ❌ **Cancel Registration** — Remove a student's enrolment and restore the seat
- 📊 **Live Tables** — Student list, course list (with available seats), and registration list update in real time

## 🚀 Getting Started

No installation needed. Open directly in any modern browser:

```
student/index.html
```

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure & Layout |
| CSS3 | Styling |
| JavaScript (Vanilla) | Registration Logic & DOM Manipulation |

## 📁 Project Structure

```
student/
└── index.html    # All-in-one HTML file (HTML + CSS + JS)
```

## 💡 How to Use

1. **Add a Student** — Enter Student ID and Name, click **Add Student**
2. **Create a Course** — Enter Course ID, Course Name, and Seat Capacity, click **Add Course**
3. **Register a Student** — Select a student and a course from the dropdowns, click **Register**
4. **Cancel Registration** — Select the student and course to unenrol, click **Cancel**

## ✅ Validations

- Student ID and Course ID must be unique
- Seat capacity must be a positive integer
- A student cannot register for the same course twice
- Registration is blocked when a course is at full capacity
- Cancelling a non-existent registration shows an error message
- Cancelled registrations restore one seat to the course

## 📊 Course Table Columns

| Column | Description |
|--------|-------------|
| Course ID | Unique identifier |
| Course Name | Name of the course |
| Capacity | Total seats |
| Available Seats | Remaining open seats |

## 📌 Notes

- Data is stored in-memory (JavaScript arrays) and resets on page refresh
- No external dependencies or internet connection required
