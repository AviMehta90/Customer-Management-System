# Customer Management System

This is a Java project created using Apache NetBeans that interacts with a MySQL database. The project allows you to manage customer and product information in an online shopping portal.

## Prerequisites

1. Download Apache Netbeans from this link https://netbeans.apache.org/download/nb120/nb120.html

2. Create a new project Java with Maven, And give whatever name you feel like to the project and under source packages/your.package.name create a new JFrame Panel

2. Add JDBC from here https://dev.mysql.com/downloads/connector/j/ and put the mysql-connector-java-8.0.21.jar file in dependencies folder inside the project and Instantiate a database locally for the project to work.

Make sure to add the `mysql-connector-java-8.0.21.jar` to the project's dependencies folder.

## Getting Started

1. Clone or download this repository to your local machine.

2. Open Apache NetBeans and select "Open Project." Navigate to the folder where you saved this project and open it.

3. Create a MySQL database for this project. You can do this using the MySQL command line or a tool like phpMyAdmin. The database should be named `newmini`.

4. Configure the database connection:
   - Open the `NewJFrame.java` file.
   - Find the database connection settings in the `jButton1ActionPerformed` and `jButton2ActionPerformed` methods.
   - Replace the connection details with your MySQL database credentials (username and password) and adjust the URL if necessary.

5. Build and run the project by clicking the "Run" button in Apache NetBeans. The application should launch.

## Usage

- The application provides a GUI interface for managing customer and product information in an online shopping portal.
- You can insert new records, delete records, and interact with the MySQL database using the provided interface.

## Troubleshooting

If you encounter any issues, check the following:

- Verify that your MySQL server is running and the database `newmini` exists.
- Ensure that you have the `mysql-connector-java-8.0.21.jar` added to the project's dependencies.

## License

This project is available under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Thanks to [Apache NetBeans](https://netbeans.apache.org/) for providing a powerful Java IDE.
- Thanks to [MySQL](https://www.mysql.com/) for the database management system.
- Thanks to the [MySQL Connector/J](https://dev.mysql.com/downloads/connector/j/) for enabling Java and MySQL connectivity.

## Disclaimer

This project is for educational and demonstration purposes. It may require further improvements and security enhancements before use in production environments.



How to make this project
https://www.youtube.com/watch?v=F4vpJJH2PZU
