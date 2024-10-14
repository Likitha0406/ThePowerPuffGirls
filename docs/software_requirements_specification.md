# Software Requirements Specification (SRS)

## Overview
This document describes the functional and non-functional requirements for the **Password Store Manager Project**. The purpose of this document is to outline the key features and performance expectations of the application, ensuring a clear understanding of the system's capabilities.

## Functional Requirements

1. **Password Retrieval**
   - **FR1:** The system shall allow users to retrieve stored passwords by entering a unique master password.

2. **Password Generation**
   - **FR2:** The application shall provide a password generator that can generate secure passwords based on user-specified criteria, such as length and character types.

3. **Password Storage**
   - **FR3:** The system shall store encrypted passwords in an SQLite database to ensure data security.

4. **Password Deletion**
   - **FR4:** The application shall allow users to delete stored passwords and delete the application securely when required.

## Non-Functional Requirements

1. **Data Encryption**
   - **NFR5:** The system shall encrypt all stored passwords using a minimum of AES-256 encryption.

2. **Performance**
   - **NFR6:** The application shall ensure that the password retrieval process takes less than 2 seconds under normal load conditions.

3. **Compatibility**
   - **NFR7:** The system shall be compatible with Windows operating systems and require minimal installation time.

4. **Usability**
   - **NFR8:** The application shall support a user-friendly interface, making it easy to navigate and perform password-related tasks with minimal training.
