# Parks & Recreation Equipment Check-Out Tool

A lightweight, console-driven Java application designed to help parks and recreation staff track, log, and manage shared equipment inventory in real time.

## Project Goal
Traditional community recreation programs often rely on chunky spreadsheets that make tracking shared instruments difficult. This tool replaces manual spreadsheets with a streamlined inventory system that tracks item availability and check-out statuses efficiently.

## MVP Scope
* **Item Management:** Add new equipment items to the local inventory with unique IDs and names.
* **Status Tracking:** Toggle item availability between *Available* and *Checked Out*.
* **Dashboard View:** Display a clean table of all current inventory items and their statuses.
* **Data Persistence:** Automatically save and load inventory data using a local CSV file.

## Tech Stack
* **Language:** Java
* **Libraries/Tools:** Standard Java libraries (`java.util.*`, `java.io.*`)
* **Data Storage:** Local CSV file

## Future Plans
* **Phase 2:** Implement user roles (Staff vs. Admin) to restrict permissions.
* **Phase 3:** Add check-out history logs tracking borrower info and due dates.
* **Phase 4:** Build a graphical user interface (GUI) or web wrapper.

## 📁 Repository Structure
├── src/
├── Eisenhower-Matrix.png
├── README.md
└── system-diagram.png
