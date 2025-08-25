# To-Do List App (Permalist)

A simple full-stack **To-Do List application** built with **Node.js, Express, PostgreSQL, and EJS**.  
It allows users to add, edit, and delete tasks, with all data stored in a PostgreSQL database.

---

## Features
- Add new tasks  
- Edit existing tasks  
- Delete tasks  
- Persistent storage using PostgreSQL  
- Clean UI with EJS templates  

---

## Tech Stack
- **Frontend**: EJS, CSS, HTML  
- **Backend**: Node.js, Express.js  
- **Database**: PostgreSQL  

---

## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/permalist.git
cd permalist
npm install
```

### 3. Configure PostgreSQL

Make sure PostgreSQL is installed and running.
Create a database named permalist and add a table:

CREATE TABLE items (
  id SERIAL PRIMARY KEY,
  title TEXT
);

### 4.Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.
