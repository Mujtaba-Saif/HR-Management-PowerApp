# 📱 HR Management Canvas Application (Fully Responsive)

A professional Power Apps Canvas application built to centralize human resource operations. This application is completely responsive, dynamically adjusting its layout to provide an optimal user experience across **Desktop, Tablet, and Mobile devices**.

## 🛠️ Application Architecture & Navigation

The app is built around a centralized **Main Dashboard (Home Screen)** that directs users across three core functional modules using fluent, conditional navigation:

1.  **Employees Screen:** For managing, searching, and filtering active employee profiles.
2.  **Employees Attendance Screen:** A dedicated interface for checking attendance of employees.
3.  **Leave Request Screen:** A streamlined submission portal for time-off requests.

## 📁 Repository Structure

*   **`/src`** - Contains the screen-by-screen YAML source code files showcasing properties, Power Fx formula logic, and layout structures.
*   **`HRManagementApp_Export_Package.zip`** - The official Microsoft Power Platform solution export, ready to be downloaded and imported directly into any environment.

## 💻 Technical Highlights & Best Practices

*   **100% Fully Responsive Design:** Developed using fluid responsive containers (`Parent.Width` / `Parent.Height` logic) instead of fixed coordinates, eliminating the need to build separate mobile and desktop versions.
*   **SharePoint Online Backend:** Engineered with optimized SharePoint lists acting as relational data tables. 
*   **Enterprise ALM Ready:** Packaged cleanly as a portable solution to demonstrate proper Application Lifecycle Management (ALM) version control standards.

---

## 🚀 How to Import and Run This App

1. Download the `HRManagementApp_Export_Package.zip` package from this repository.
2. Go to your [Power Apps Studio](https://make.powerapps.com/).
3. Select **Apps** from the left navigation menu, then click **Import canvas app**.
4. Upload the `.zip` file, configure your data connection parameters to point to your target SharePoint site, and publish.
