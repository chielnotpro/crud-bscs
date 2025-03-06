# **Laravel 11 Activity: CRUD Implementation**  

## **Objective**  
Each student will implement a specific task in a Laravel 11 CRUD application. The project will be managed using GitHub, where students will create their own branches and submit a pull request upon completion.  

---

### **Student Tasks**  

| **Student Name**                  | **Assigned Task**                              |
|------------------------------------|-----------------------------------------------|
| Adorias, Jerome Giovanni C.        | Create the **User Model**  && INSTALL AND SETUP LARAVEL                    |
| Bolinas, Justine Aris              | Create the **User Controller**                |
| De La Cruz, Leovin C.              | Create the **User View (Blade Template)**     |
| Dumogho, Marlo Eleuterio L.        | Create the **Migration Schema for Users**     |
| Geroche, Althea Gwyneth T.         | Implement the **Create User Form**            |
| Geroche, Karen B.                  | Implement the **Edit User Form**              |
| Gomez, Richard Josh P.             | Implement the **User Listing Table**          |
| Lacague, Jkie F.                   | Implement **User Deletion Functionality**     |
| Laplana, Kent Christopher D.       | Implement **User Validation Rules**           |
| Larido, Churchiel D.               | Implement **Route Definitions for CRUD (web.php)**  |
| Lazaro, Chasten J.                 | Implement **User Sanitization Rules**        |
| Mabug-at, Axel R.                  | Implement **User Validation Rules**  |
| Macay, Nicamae T.                  | Implement the **Edit User Form**     |
| Saracanlao, Novel O.               | Implement **Route Definitions for CRUD (web.php)** |
| Sera, Darlene Joy S.               | Implement **Seeder for Users Table**         |
| Villamin, Kimberly Gale D.         | Implement the **Create User Form**            |

## **Git Workflow**
Your must follow the workflow to submit your code.

## **Submission Deadline**
📌 All pull requests must be submitted by **MARCH 6, 2025 | 3:00PM**.

---

# **Grading Rubric**

## **Evaluation Criteria**
You will be graded based on the accuracy, functionality, readability, and completeness of their assigned task.

| **Criteria**            | **Excellent (10 pts)**                              | **Good (8 pts)**                                 | **Fair (7 pts)**                               | **Needs Improvement (5 pts)**                 |
|-------------------------|-----------------------------------------------------|------------------------------------------------|------------------------------------------------|------------------------------------------------|
| **Model Creation**      | Model is properly defined with correct attributes and relationships. Uses mass assignment protection and appropriate casting. | Model is defined correctly but lacks mass assignment protection or casting. | Model is created but contains minor errors in attribute definitions or relationships. | Model is incomplete or contains significant errors. |
| **Controller Implementation** | Controller methods follow Laravel best practices, correctly handling CRUD operations and validation. Uses dependency injection and clean code structure. | Controller handles CRUD operations but lacks some best practices such as validation in the correct places. | Controller is functional but contains redundant code or improper structure. | Controller has major errors or lacks CRUD implementation. |
| **View (Blade Template)** | Blade template is well-structured, dynamic, and includes proper form handling, loops, and conditionals. Uses @csrf and @method directives. | View is functional but lacks structure or contains minor issues like missing CSRF protection. | View has incorrect form handling or minor missing elements. | View is incomplete or not functional. |
| **Migration Schema**    | Schema defines all necessary columns with correct data types and constraints (e.g., unique, nullable, default values). | Schema is mostly correct but has minor issues in data types or constraints. | Schema is incomplete or missing some necessary fields. | Migration is missing or incorrectly structured. |
| **Create User Form**    | Form is fully functional, properly structured, and includes validation messages. Uses Laravel's old() helper for input persistence. | Form is functional but lacks styling or proper validation messages. | Form has minor issues like missing validation or incorrect input names. | Form is incomplete or does not submit data correctly. |
| **Edit User Form**      | Edit form correctly pre-fills user data and updates records successfully. Uses proper validation and error handling. | Edit form works but has minor issues like missing validation or pre-filled values. | Edit form is functional but has UI issues or lacks validation. | Edit form does not work properly or is missing key functionality. |
| **User Listing Table**  | Displays users dynamically with correct data. Includes pagination and sorting. Uses Bootstrap or Tailwind for styling. | Table works but lacks pagination or has minor layout issues. | Table displays data but does not update dynamically or has styling issues. | Table is incomplete or does not display user data correctly. |
| **User Deletion**       | Deletes users properly using soft deletes. Includes a confirmation modal. | Deletes users but lacks a confirmation prompt or does not use soft deletes. | Deletion works but has minor UI/UX issues. | Deletion does not work properly or has security flaws. |
| **User Validation Rules** | Uses Laravel's validation rules properly with clear error messages and reusable validation requests. | Validation works but has minor issues like missing rules or unclear messages. | Validation is present but lacks completeness (e.g., missing required fields). | Validation is incorrect or missing entirely. |
| **Route Definitions (web.php)** | Defines all necessary routes properly, using named routes and correct middleware. | Routes are mostly correct but missing naming conventions or middleware. | Routes work but are poorly structured or redundant. | Routes are incorrect or missing key definitions. |
| **User Sanitization Rules** | Uses Laravel's built-in sanitization methods like `filter_var()` or `Str::of()`. Prevents XSS and SQL Injection. | Sanitization is present but lacks some best practices. | Sanitization is minimal or inconsistently applied. | No proper sanitization applied, making the app vulnerable. |
| **Seeder for Users Table** | Uses factory and seeder to generate realistic dummy users with random but valid data. | Seeder works but generates only minimal or repetitive data. | Seeder is present but does not follow best practices. | Seeder is incomplete or does not generate users correctly. |

### **Total Score:**
- **90 - 100 points**: Outstanding performance
- **80 - 89 points**: Good work, but minor improvements needed
- **70 - 79 points**: Functional but lacks best practices
- **Below 70 points**: Needs major improvements

### **Additional Notes:**
- **Code Readability & Comments**: Clean, well-documented code will receive additional consideration.
- **Version Control & Git Best Practices**: Each student must create their branch, commit frequently, and submit a pull request for review.

