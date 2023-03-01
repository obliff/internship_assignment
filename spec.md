# User Management Screen UI Specification

## **Overview**
The user management screen allows administrators to view, add, edit and delete user information. The screen is divided into two sections: the left section displays a table of existing users, and the right section provides a form for adding or editing user information.

---

## **UI Components** 
## Buttons
* New User Button: Located in the left upper corner of the screen, a blue button that opens a new user form for user creation.
* Hide Disabled User Checkbox: Located just right to the "New User" button. It allows the user to toggle the display of disabled users in the user list.
* Save User Button: Located in the right upper corner of the screen, a pale blue button that saves changes made to the user accoun

## Table
* ID: This column displays a unique identifier for each user.
* User Name: This column displays the user's username
* Email: This column displays the user's email address.
* Enabled: This column displays whether the user's account is enabled or disabled.
* User List Table: Displays a list of all user accounts with columns for ID, User Name, Email, and Enabled. Users can sort and filter the list by clicking on column headers.

## Form
* Username Field: A text input field for the user to enter a unique username for the new user account.
* Display Name Field: A text input field for the user to enter a display name for the new user account.
* Phone Field: A text input field for the user to enter a phone number for the new user account.
* Email Field: A text input field for the user to enter an email address for the new user account.
* User Roles Field: A dropdown list with three options for user roles: Guest, Admin, and SuperAdmin.
* Enabled Checkbox: A checkbox for the user to enable or disable the user account.

## **User Interface Behavior**
**User List**
* The user list is displayed by default when the user opens the User Management Screen.
* Users can sort the list by clicking on the column headers for ID, User Name, Email, or Enabled.
* Users can filter the list by enabling or disabling the "Hide Disabled Users" checkbox.

**User Form**
* The user form is displayed when the user clicks on the "New User" button.
* When the user submits the form by clicking the "Save User" button, a new user account is created with the provided information.
* The user form is cleared and closed when the new user account is successfully created.
* If any required fields are missing or invalid, an error message is displayed to the user.

## **Initial Display**
The initial display of the User Management Screen shows the user list with the following two example user accounts:

| ID | User Name | Email | Enabled |  
| -------------- | -------------- | -------------- |-------------- |
| 1 | AdminUser | admin@piworks.net | true |
| 2 | Test User | testuser@piworks.net | true |

The "New User" button, "Hide Disabled Users" checkbox, and "Save User" button are also displayed.

---

## **Conclusion**
In conclusion, this document provides a detailed specification of the User Management Screen UI components and their behavior. It includes a description of the buttons, user list, and user form, as well as their functionalities. This document will serve as a guide for software developers who will implement this user interface. It is expected that the UI will be user-friendly and intuitive, making it easier for users to manage user accounts.




