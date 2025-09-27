# Animal Tracking System

A **Windows Forms application** for managing animal records, including ID, species, location, health status, and last sighting date. The application supports full **CRUD operations** and integrates with a SQL Server database.

---

## Features
- Add new animal records
- View all stored records in a DataGridView
- Update existing animal details
- Delete records from the database
- Database connectivity via SQL Server
- User-friendly WinForms interface

---

## Database Structure
| Field Name       | Data Type | Description                   |
|-----------------|-----------|-------------------------------|
| AnimalID        |  nvarchar | Unique identifier for animals |
| Species         | nvarchar  | Species name                  |
| Location        | nvarchar  | Last known location           |
| HealthStatus    | nvarchar  | Health condition of animal    |
| LastSightingDate| date      | Date of last sighting         |

---

## Database Setup

The project includes a `.bak` file for easy database restoration:

1. Open **SQL Server Management Studio (SSMS)**.
2. Right-click on `Databases` → **Restore Database**.
3. Select **Device** → Browse to `database/AnimalTrackingSystem.bak`.
4. Click **Restore**.
5. Update the connection string in `App.config` if needed.

---

## Screenshots
<img width="556" height="390" alt="image" src="https://github.com/user-attachments/assets/43738d0b-795b-4421-b5c9-5b6ec4d23147" />
<img width="541" height="499" alt="image" src="https://github.com/user-attachments/assets/f7bf6c63-acb1-4020-bac2-3234aff337ad" />

---

## Technologies Used
- **Frontend:** C# WinForms  
- **Backend / Database:** SQL Server  
- **Concepts:** CRUD operations, ADO.NET, DataGridView, form validation  

---

## How to Run
1. Restore the database using the `.bak` file.
2. Open the solution in **Visual Studio**.
3. Build and run the project.
4. Start managing animal records!

---

## Optional Enhancements
- Search or filter animals by species, location, or health status
- Export data to CSV or Excel
- Add images for each animal
- Sorting in DataGridView

---

## Author
**Dulan Dhanush Kandeepan**  
(https://www.linkedin.com/in/dulan-dhanush-b76a44300?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
