# SupermarketManagementSystem

## Overview

The Supermarket Management System is a comprehensive solution designed for managing supermarket operations. This system allows for efficient handling of various tasks such as billing, product management, sales analysis, and customer interaction. The application utilizes a graphical user interface (GUI) built with Tkinter and integrates with a MySQL database to handle data storage and retrieval.

## Features

- **Billing**: Generate and manage bills, track products, and handle customer details.
- **Statistics**: Analyze sales, bills, and product statistics.
- **Product Management**: Add, view, edit, and delete products.
- **Dashboard**: View detailed sales and product statistics.
- **Barcode Scanning**: Use barcode scanning for adding products to bills.
- **Database Integration**: Connects to a MySQL database for data management.
- **Real-time Video**: Captures and displays real-time video from the webcam for barcode scanning.

## Technologies Used

- **Python**: Programming language used for the application.
- **Tkinter**: GUI toolkit for creating the application’s interface.
- **OpenCV**: For capturing video from the webcam.
- **Pygame**: For playing the scanner sound.
- **PIL (Pillow)**: For image processing.
- **PyZbar**: For barcode decoding.
- **Matplotlib**: For generating statistical plots.
- **Pandas**: For data manipulation and analysis.
- **Pymysql**: For MySQL database connectivity.
- **MySQL**: Database management system.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/SupermarketManagementSystem.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd SupermarketManagementSystem
   ```

3. **Install Required Packages**:
   ```bash
   pip install -r requirements.txt
   ```

   Create a `requirements.txt` file with the following content:
   ```
   opencv-python
   pygame
   pillow
   pyzbar
   pandas
   matplotlib
   pymysql
   ```

4. **Set Up the Database**:
   - Ensure you have MySQL installed and running.
   - Create a database named `pbl` and set up the necessary tables. The SQL schema can be found in `db_schema.sql` (if provided).

## Usage

1. **Run the Application**:
   ```bash
   python main.py
   ```

2. **Interface Navigation**:
   - Use the menu bar to navigate through different sections: Billing, Statistics, Product Management, and About.
   - For billing, use the barcode scanner or manually enter product details.

3. **Database Connection**:
   - Update the database connection details in the `db_conn_funct()` function if needed.

## Contributing

1. **Fork the Repository**.
2. **Create a New Branch**:
   ```bash
   git checkout -b feature/new-feature
   ```
3. **Commit Your Changes**:
   ```bash
   git add .
   git commit -m "Add a new feature"
   ```
4. **Push to the Branch**:
   ```bash
   git push origin feature/new-feature
   ```
5. **Create a Pull Request**.


## Acknowledgements

- OpenCV and Pygame for their image processing and audio capabilities.
- Tkinter for creating the GUI.
- PyZbar for barcode decoding.
- Pandas and Matplotlib for data manipulation and visualization.
