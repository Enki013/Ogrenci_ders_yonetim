**Course Registration Form**

This Java Swing application provides an interface to enter, save, and view course information.

**Classes**

**1\. Course**

This class represents the attributes of a course (course code, course name, semester, lecturer).

-   **courseCode:** The unique code of the course.
-   **courseName:** The name of the course.
-   **courseSemester:** The semester of the course.
-   **lecturer:** The lecturer of the course.

**2\. CourseForm**

This class creates a course registration form using Java Swing JFrame.

Attributes

-   **courseCodeField:** Input field for course code.
-   **courseNameField:** Input field for course name.
-   **courseSemesterField:** Input field for course semester.
-   **lecturerComboBox:** Combo box for selecting the lecturer.
-   **saveButton:** Button to save the course.
-   **courseTable:** Table to display saved course information.
-   **filterTextField:** Text field to filter courses.
-   **tableModel:** Data model for the course table.

Methods

-   **createStyledButton(String buttonText):** Creates a styled button.
-   **validationCheck():** Validates user inputs.
-   **saveCourse():** Saves the entered course information to a JSON file.
-   **readLecturers(String fileName):** Reads lecturers from a JSON file.
-   **writeCourse(JSONObject courseJson):** Writes course information to a JSON file.
-   **refreshCourseTable():** Refreshes the course table.
-   **readCourses(String fileName):** Reads saved course information from a JSON file.
-   **filterCourseTable():** Filters the course table based on text input.
-   **createLabel(String text):** Creates a label.

Main Method

-   **main(String[] args):** The main method that starts the application.

**How to Use**

1.  When the application starts, enter the required information to add a course.
2.  Click the "Save" button to save the entered course information.
3.  The saved courses will be displayed in the table.
4.  You can filter the courses using the "Search" field.

**Dependencies**

-   JSON Simple Library: Used for JSON operations (reading and writing JSON files).

**Lecturer Registration Form**

This Java Swing application provides an interface to enter, save, and view lecturer information.

**Classes**

**1\. LecturerForm**

This class creates a lecturer registration form using Java Swing.

Attributes

-   **teacherNoField:** Field to enter the unique number of the lecturer.
-   **nameField:** Field to enter the lecturer's first name.
-   **surnameField:** Field to enter the lecturer's last name.
-   **departmentField:** Field to enter the lecturer's department.
-   **saveButton:** Button to save lecturer information.
-   **lecturerTable:** Table to display saved lecturer information.
-   **filterTextField:** Text field to filter lecturers.
-   **tableModel:** Data model for the lecturer table.

Methods

-   **saveLecturer():** Saves the entered lecturer information to a JSON file.
-   **refreshLecturerTable():** Refreshes the lecturer table with the latest data.
-   **createLabel(String text):** Creates a styled label.
-   **createStyledButton(String buttonText):** Creates a styled button.
-   **readLecturers(String fileName):** Reads lecturer information from a JSON file.
-   **filterLecturerTable():** Filters the lecturer table based on user input.

Main Method

-   **main(String[] args):** The main method that starts the application.

**How to Use**

1.  When the application starts, enter the required information to add a new lecturer.
2.  Click the "Save" button to save the lecturer information.
3.  View the saved lecturer information in the table.
4.  Use the "Search" field to filter lecturers.

**Dependencies**

-   JSON Simple Library: Used for JSON operations (reading and writing JSON files).

**Note**

-   Lecturer information is stored in a JSON file named "lecturers.json".
-   The application provides basic validation and filtering functionality.

**Student Registration Form**

This Java Swing application provides an interface to enter, save, and view student information.

**Classes**

**1\. StudentForm**

This class creates a student registration form using Java Swing.

Attributes

-   **studentNumberField:** Field to enter the student number.
-   **studentNameField:** Field to enter the student's first name.
-   **studentSurnameField:** Field to enter the student's last name.
-   **studentDepartmentField:** Field to enter the student's department.
-   **studentCoursesField:** Field to select the courses the student is taking.
-   **saveButton:** Button to save student information.
-   **studentTable:** Table to display saved student information.
-   **filterTextField:** Text field to filter students.
-   **tableModel:** Data model for the student table.

Methods

-   **readCourses():** Reads and returns a list of courses.
-   **createStyledButton(String buttonText):** Creates a styled button.
-   **createStyledComboBox():** Creates a styled combo box.
-   **validationCheck():** Validates inputs.
-   **saveStudent():** Saves the entered student information to a JSON file.
-   **refreshStudentTable():** Refreshes the student table with the latest data.
-   **readStudents(String fileName):** Reads student information from a JSON file.
-   **printStudent(JSONObject studentJson):** Prints student information to the screen.
-   **filterStudentTable():** Filters the student table based on user input.
-   **createLabel(String text):** Creates a styled label.

Main Method

-   **main(String[] args):** The main method that starts the application.

**How to Use**

1.  When the application starts, enter the required information to add a new student.
2.  Click the "Save" button to save the student information.
3.  View the saved student information in the table.
4.  Use the "Search" field to filter students.

**Dependencies**

-   JSON Simple Library: Used for JSON operations (reading and writing JSON files).

**Note**

-   Student information is stored in a JSON file named "students.json".
-   The application provides basic validation and filtering functionality.

You can customize and expand according to your needs.
