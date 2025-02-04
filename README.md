# Expense Management System

A comprehensive Expense Management System featuring a *Streamlit frontend* and a *FastAPI backend* for efficient expense tracking and management.

## 🚀 Project Overview

- *frontend/*: Houses the Streamlit application code for the user interface.  
- *backend/*: Contains the FastAPI server code responsible for handling API requests.  
- *tests/*: Includes unit and integration tests for both the frontend and backend components.  
- *requirements.txt*: Lists all the necessary Python dependencies required to run the project.  
- *README.md*: This document provides setup instructions and an overview of the project.  

## ⚙️ Getting Started

Follow these steps to set up the project on your local machine:

1. *Clone the Repository*  
   bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   

2. *Install Project Dependencies*  
   bash
   pip install -r requirements.txt
   

3. *Start the FastAPI Backend Server*  
   bash
   uvicorn server.server:app --reload
   

4. *Launch the Streamlit Frontend Application*  
   bash
   streamlit run frontend/app.py
