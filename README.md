# Design For Social Innovation Project

## NGO: Choice Foundation  
**Group:** 1  

[Presentation + Video Demo Link | OneDrive](https://iiitaphyd-my.sharepoint.com/:f:/g/personal/prithvi_karthik_students_iiit_ac_in/Er3T3tpZgkpFnVNvZIMJRPABPqzakZ9y2IpiyKPHVva4xg?e=qKzoEC)  

## Installation  

### Prerequisites  
Ensure the following are installed on your system:  
- **Python** (3.x)  
- **npm** (Node.js)  
- **MongoDB Remote**  

### Installation Steps  

1. Change to code repository  
   ```bash
   cd dfsi
   ```
2. Install frontend dependencies
   ```bash
   npm install
   ```
3. Navigate to backend directory and install dependencies
   ```bash
   cd backend
   pip install -r requirements.txt
   ```
4. Copy `backend/sample.env` file to `backend/.env` and add MongoDB connection details

### Steps to Run

1. Start backend
   ```bash
   cd backend
   python3 app.py
   ```
2. Start frontend  
   ```bash
   cd dfsi
   npm start
   ```
