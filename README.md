# SAP-Dynpro-Module-Pool-System

A structured SAP ABAP Module Pool application that demonstrates dynamic screen handling, tabstrip navigation, and ALV-based data visualization using SAP Dynpro (Dialog Programming).

---

## 📌 Overview

- This project is an SAP ABAP Module Pool Program developed to demonstrate dynamic screen flow, tabstrip navigation, and structured data processing using SAP Dynpro (Dialog Programming).  

- The application uses multiple screens and tab-based navigation to efficiently manage and display business data such as Material (MARA) and Sales Document (VBAK).  

---

## ⚙️ Features

- 🧭 Dynamic Tabstrip Navigation  
  - Switch between multiple subscreens using tab controls  

- 🖥️ SAP Dynpro-Based UI  
  - Interactive screen-based application (SE51)  

- 🔄 Modular Screen Flow Logic  
  - Clear separation of PBO and PAI modules  

- 📊 Business Data Handling  
  - Integration with standard SAP tables:  
    - MARA (Material Master)  
    - VBAK (Sales Document Header)  

- 📈 ALV Reporting  
  - Interactive ALV Grid with sorting, filtering, and layout customization  
  - Enhances data analysis and user experience  

- ⚡ Event-Driven Processing  
  - Handles user actions via OK_CODE and SY-UCOMM  

---

## 🧠 Core Concepts Used

- Module Pool Programming (Dialog Programming)  
- Screen Painter (SE51)  
- Tabstrip Controls  
- PBO (Process Before Output)  
- PAI (Process After Input)  
- Subscreen Management  
- SAP Data Dictionary Integration  

---

## 🛠️ Tech Stack

- **Language:** ABAP  
- **Platform:** SAP ERP / S/4HANA  
- **UI Technology:** Dynpro (Screen Programming)  

- **Tables Used:**  
  - MARA – Material Master  
  - VBAK – Sales Document  

---

## 🔄 How It Works

1. Program Initialization  
   - The application starts with the main screen (Screen 100)  
   - Global data and screen elements are initialized  

2. Tabstrip Navigation  
   - Users switch between subscreens using tab controls  
   - Each tab represents a functional view:  
     - Material Data (MARA)  
     - Sales Data (VBAK)  

3. PBO (Process Before Output)  
   - Determines active tab  
   - Loads corresponding subscreen  
   - Prepares data for display (including ALV)  

4. PAI (Process After Input)  
   - Captures user actions via OK_CODE / SY-UCOMM  
   - Updates navigation and triggers logic  

5. Data Processing & Display  
   - Fetches data from SAP tables  
   - Displays output using ALV Grid:  
     - Sorting  
     - Filtering  
     - Structured visualization  

6. Screen Flow Control  
   - Continuous cycle between PBO and PAI  
   - Ensures smooth and dynamic UI behavior  

---

## 🚀 Use Cases

- SAP Module Pool Programming Practice  
- Dynpro Screen Handling Learning  
- Tab-Based UI Demonstration  
- Custom SAP Transaction Development  

---
