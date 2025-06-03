The Inventory Management System is a Python-based project built using Tkinter, which provides a simple graphical user interface (GUI). This system makes it easier for businesses to manage their inventory, including products, suppliers, employees, and sales. It also handles billing, allowing businesses to keep track of sales transactions and invoices.

The system is made up of 8 Python scripts that all work together to make the system function smoothly. These scripts use different Python libraries like Tkinter for the interface, Pillow (PIL) for image handling, SQLite3 for the database, and os for file management. Each script has a specific job, such as managing employees, products, or sales.

The main goal of this system is to simplify inventory management. Businesses can use it to keep track of stock, suppliers, and employees, making their workflow more efficient. The user interface is easy to use, and everything you need is just a click away. You can add new products, employees, suppliers, and even manage sales and billing, all in one place.

 

How to Run the Code
Running the Inventory Management System on your computer is straightforward. Here are the steps:

Install Python Libraries: Before you run the system, you need to install some Python libraries. Open your terminal or command prompt and run the following commands:

 
pip install time
pip install pil
pip install sqlite3
pip install os
Set Up the Database:

Go to the folder where you have saved the project files.

First, run the create_db.py script. This will create the database and tables needed for the system to work.

Open your terminal and run this command:

python create_db.py
Start the Dashboard:

Once the database is set up, run the dashboard.py script to open the main interface.

Use the following command:

 
python dashboard.py
Add and Manage Data:

In the dashboard, you can add and manage data like employees, suppliers, products, and sales.

Click on the relevant buttons to add or update data, or view your sales and billing records.
