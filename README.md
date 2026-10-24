E-Commerce Shopping Cart System (Core Java)
A menu-driven console project demonstrating OOP, Collections, exception handling, and file handling.

Requirements
JDK 17 or later (uses modern switch syntax)
VS Code with the Java Extension Pack, or Eclipse / IntelliJ
Run in Windows (Command Prompt / PowerShell)
Extract ECommerceShoppingCartSystem.zip.
Open the extracted ECommerceShoppingCartSystem folder.
Open a terminal in that folder.
Compile:
javac -d out src/main/java/Main.java
Run:
java -cp out Main
If you use VS Code, open the extracted project folder (File > Open Folder), open src/main/java/Main.java, and use the Run button. If asked, install the Java Extension Pack and select a JDK.

Default admin login
Username: admin
Password: admin123
Features
User registration and login
Product catalog
Add/remove products from cart
Cart total and checkout
Order history
Admin product add/update/delete
Admin order report and total revenue
Persistent local storage in shopping_cart_data.ser
Data and security notes
The .ser data file is created automatically in the folder from which you run the program.
This is a learning project, not production e-commerce software. Passwords are stored as plain text in the local serialized data file; do not use real passwords or personal information.
To reset the sample data, close the program and delete shopping_cart_data.ser. The sample products will be created again on the next run.
Suggested GitHub repository description
Core Java console-based e-commerce shopping cart with user authentication, product management, checkout, order history, admin reports, Collections, OOP, and file persistence.
