# Library Management System

This project is a Library Management System developed in Java with HTML, CSS, and Spring Boot following the MVC architecture. It incorporates various Object-Oriented Programming (OOP) concepts, design patterns, and features such as CSV file handling, exception handling, and more.

## Features

- **User Roles**: 
    - **Admin**: Manages librarians and approves librarian requests.
    - **Librarian**: Handles book borrowing requests and manages library resources.
    - **Member**: Can borrow books from the library.

- **User Authentication**: Different login options for admin, librarian, and member.

- **User Registration**: Members and librarians can sign up for the system.

- **Librarian Approval**: Admin approves librarian requests for job applications.

- **Book Borrowing**: Members can request to borrow books, and librarians can manage these requests.

- **Sorting**: Sorting of books and applications based on various criteria.

- **Private Space Booking**: Feature to book private spaces in the library.

## Technologies Used

- **Backend**: Java, Spring Boot
- **Frontend**: HTML, CSS
- **Database**: CSV files

## Design Patterns

- **MVC (Model-View-Controller)**: The application is designed using the MVC architecture to separate concerns and facilitate better maintainability.
- **Singleton**: Singleton pattern is used where only one instance of a class is created.
- **Factory**: Used for creating different types of users (admin, librarian, member).
- **Strategy**: Used for sorting books and applications.
- **Observer**: Used for notifying admins about new librarian requests.

## Object-Oriented Programming Concepts

- **Inheritance**: Used for creating different types of users.
- **Polymorphism**: Implemented through method overriding and overloading.
- **Encapsulation**: Data hiding and abstraction principles are applied throughout the project.
- **Interfaces**: Used for defining contracts such as sorting strategies.
- **Inner Classes**: Utilized for creating classes within classes for better organization.

## Exception Handling

- **Try-Catch Blocks**: Used to handle exceptions gracefully throughout the application.

## CSV File Handling

- **Read/Write Operations**: CSV files are used to store data such as user information, book details, etc. Reading and writing to these files are implemented.

## Lambdas

- **Functional Interfaces**: Lambdas are used with functional interfaces for sorting.

## Project Structure

- **src/main/java**: Contains Java source code.
    - **Controller**: Contains controllers for handling requests.
    - **Model**: Contains model classes representing users, books, etc.
    - **Service**: Contains service classes for business logic.
    - **Util**: Contains utility classes for CSV file handling, sorting, etc.
- **src/main/resources**: Contains static files like HTML, CSS, etc.

## How to Run

1. Clone the repository.
2. Open the project in your IDE.
3. Build and run the project.
4. Access the application through the provided URL.(localhost:8080) kill any existing processes running in that port. 
5. adjust the relative path of files in application.properties

## Contributors

- Lakshmi GayatriAishwarya Adduri (adduri.l@northeastern.edu)
- SAICHARANTEJ
- varunsaibuduru
- ShreyaSisodiya
- Saibhavanesh

## License

This project is licensed under the [MIT License](LICENSE).

#Link to Video Presentation: https://northeastern-my.sharepoint.com/personal/adduri_l_northeastern_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Fadduri_l_northeastern_edu%2FDocuments%2FRecordings%2FCall%20with%20Sai%20and%203%20others-20240422_131435-Meeting%20Recording%2Emp4&referrer=Teams%2ETEAMS-ELECTRON&referrerScenario=MeetingChicletExpiration%2Eview%2Eview&ga=1

## Acknowledgements

- Special thanks to Prof Daniel Peters.

Feel free to contribute, report issues, or suggest improvements!

---

Feel free to adjust the README according to your specific project details and preferences.
