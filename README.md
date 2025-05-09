# Winery Management Desktop Application

A standalone desktop application developed in Java for managing core operations of a winery, including inventory, customer data, and sales records. The application integrates with a Microsoft Access database and is packaged as an executable JAR for ease of deployment.

## Overview

This project was developed using Java and Eclipse IDE. It connects to a local `.accdb` database file via JDBC, providing a lightweight and self-contained solution suitable for small-to-medium scale winery operations or academic demonstration purposes.

## Key Features

- Add, update, and manage wine records and categories
- Maintain customer information and purchase history
- Interface with Microsoft Access database via JDBC (UCanAccess or ODBC)
- Organized storage of structured data in XML and JSON format (optional)
- Packaged as an executable JAR for immediate use

## Technologies Used

- **Language:** Java
- **IDE:** Eclipse
- **Database:** Microsoft Access (`.accdb`)
- **Persistence:** JDBC with optional UCanAccess driver
- **Packaging:** Runnable JAR
- **File Formats:** XML, JSON

## Project Structure

/WineryManagementDesktopApp/
│
├── src/ # Java source files
├── database1/
│ ├── database/
│ │ └── ex3_324991892_212015739_one.accdb # Microsoft Access database
│ ├── json/ # Optional JSON storage
│ ├── xml/ # Optional XML storage
│ └── WineryDesktopApp.jar # Compiled executable JAR file
├── README.md
└── .gitignore

## Getting Started

### Requirements

- Java SE Development Kit 8 or higher
- Microsoft Access Database Engine (64-bit recommended)
- (Optional) UCanAccess JDBC driver for running from source

### Running the Application

To launch the application:

```bash
java -jar database1/WineryDesktopApp.jar
Note: The Access database file must remain in database1/database/ as expected by the internal JDBC path configuration.

## License

This project is provided for educational and demonstration purposes. It may be reused with appropriate attribution.

## Author

Claudetannous  
Developed in Java using Eclipse IDE
