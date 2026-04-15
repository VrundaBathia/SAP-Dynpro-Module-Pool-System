# SAP-Dynpro-Module-Pool-System
## 📌 Overview

- This project is an SAP ABAP Module Pool Program designed to demonstrate dynamic screen handling, tabstrip navigation, and structured data interaction using SAP Dynpro (Dialog Programming).

- The system uses multiple screens and tab-based navigation to manage and display business data such as Material (MARA) and Sales Document (VBAK) information.
--
## ⚙️ Features

🧭 Dynamic Tabstrip Navigation
- Switch between multiple subscreens using tab controls

-- 🖥️ SAP Dynpro-Based UI
Interactive screen-based application (SE51)
🔄 Modular Screen Flow Logic
Clean separation of input/output modules
📊 Business Data Handling
Integration with standard SAP tables:
MARA (Material Master)
VBAK (Sales Document Header)
📊 ALV Reporting
Interactive ALV Grid with sorting, filtering, and layout customization
Enhances data analysis and user experience
⚡ Event-Driven Processing
Handles user actions via OK_CODE and SY-UCOMM

🧠 Core Concepts Used
Module Pool Programming (Dialog Programming)
Screen Painter (SE51)
Tabstrip Controls
PBO (Process Before Output)
PAI (Process After Input)
Subscreen Management
SAP Data Dictionary Integration
🛠️ Tech Stack
Language: ABAP
Platform: SAP ERP / S/4HANA
UI Technology: Dynpro (Screen Programming)
Tables Used:
MARA – Material Master
VBAK – Sales Document

🔄 How It Works
1. Program Initialization
The application starts with the main screen (Screen 100) of the Module Pool program.
Global data and screen elements are initialized.
2. Tabstrip Navigation
A tabstrip control allows users to switch between different functional views.
Each tab is linked to a specific subscreen:
Material Data View (MARA)
Sales Data View (VBAK)
3. PBO (Process Before Output)
Determines which tab is active.
Dynamically loads the corresponding subscreen.
Prepares data for display (including ALV output if triggered).
4. User Interaction (PAI – Process After Input)
Captures user actions through OK_CODE / SY-UCOMM.
Updates the active tab and handles navigation logic.
5. Data Processing & Display
Retrieves relevant data from SAP tables (MARA, VBAK).
Displays structured output using ALV Grid, enabling:
Sorting
Filtering
Easy data analysis
6. Screen Flow Control
The program continuously cycles between PBO and PAI modules.
Ensures smooth navigation, real-time updates, and responsive UI behavior.

🚀 Use Cases
SAP training for Module Pool Programming
Learning Dynpro screen handling
Demonstrating tab-based UI navigation
Building custom SAP transactions
