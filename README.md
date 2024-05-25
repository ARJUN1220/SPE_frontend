# WorkWize - Industrial Project Management Platform
## Front End

### [Back End Repository](https://github.com/NaikVRaj/majorProject)

## Table of Contents

1. [Problem Statement](#problem-statement)
2. [Application Features](#application-features)
3. [DevOps Tool Stack](#devops-tool-stack)
4. [Front End](#front-end)
   - [Introduction](#introduction)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
   - [Running the Application](#running-the-application)
   - [Building the Application](#building-the-application)
   - [Running Tests](#running-tests)
   - [Tool Stack](#tool-stack)
5. [Application UI](#application-ui)

---

## Problem Statement

In industrial settings, traditional methods of project management often lack efficiency and responsiveness, characterized by manual processes and disjointed workflows. Existing project management systems may not adequately address the needs of industrial projects, leading to challenges in project coordination, task assignment, and progress tracking. Additionally, there is a growing demand for platforms that can accommodate user feedback and updates in real-time.

The project "WorkWize" aims to address these challenges by developing a comprehensive project management platform tailored for industrial settings. The primary objective is to provide a streamlined and intuitive solution that enhances project workflows and facilitates effective project management by all stakeholders.

---


## Application Features

### Roles:

1. **Employee:**
   - **Role Description:** Employees execute assigned tasks within projects under the guidance of managers.
   - **Functionalities:**
     - Tasks Related:
       - View Assigned Tasks
       - Update Task Progress
       - Visualize Personal Progress
     - View Profile:
       - View personal details
       - View task history
     - Reset Password:
       - Request password reset
       - Set new password

2. **Manager:**
   - **Role Description:** Managers oversee projects and task assignments, ensuring smooth workflow and project progress.
   - **Functionalities:**
     - Create Project:
       - Create new projects
       - Assign to employees
     - Update Project:
       - Edit existing projects
       - Add or remove tasks, employee from projects
     - Delete Project:
       - Delete Project from the System
     - Project Progress Monitoring
     - Time Distribution Management
     - Effort Distribution Visualization
     - Reset Password:
       - Request password reset
       - Set new password

3. **Admin:**
   - **Role Description:** Administrators have the highest level of access and are responsible for managing users, including adding and removing employees and managers, as well as overseeing the overall system administration.
   - **Functionalities:**
     - Manage Users:
       - Add new users
       - View user profiles
       - Edit user profiles
       - Delete user accounts
     - System Administration:
       - Handle system configurations
       - Perform maintenance tasks
       - Address technical issues and escalations

---

## Diagrams

### Use Case Diagram
![Use Case Diagram](Images/Diagrams/UseCaseDiagram.png)

### DB Design
![DB Design](Images/Diagrams/DBDesignWithMapping.jpg)

### API Documentation
![API Documentation](Images/Diagrams/API.png)

---

## DevOps Tool Stack

### Front End:
- Angular JS

### Back End:
- Framework:
  - Spring Boot
- Database:
  - MySQL

### DevOps Tool:
- GitHub: Version control and collaboration
- Jenkins: Automation for building, testing, and deployment
- Docker: Containerization for application management
- Ansible: Automation for configuration and deployment
- ELK Stack: Log management and analysis

---

## Front End
### Introduction

WorkWize is a comprehensive project management platform tailored for industrial settings. This repository contains the front end of the application, which is built using Angular. The front end interacts with the back end services to provide a seamless user experience for managing projects, tasks, and users.

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (>= 14.0.0)
- npm (>= 6.0.0) or Yarn (>= 1.0.0)
- Angular CLI (>= 12.0.0)

### Installation

Follow these steps to set up the project on your local machine:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/ARJUN1220/SPE_frontend.git
    cd SPE_frontend
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

### Running the Application

To run the application locally, use the following command:

```bash
npm start
```

This will start the development server and you can access the application at `http://localhost:4200/`.

### Building the Application

To build the application for production, use the following command:

```bash
npm run build
```

The build artifacts will be stored in the `dist/` directory.

### Running Tests

To run the unit tests using Karma, use the following command:

```bash
npm test
```

This will execute the unit tests and generate a report.

### Tool Stack

#### Front End:
- **Framework**: Angular
- **Styling**: Angular Material, Bootstrap

#### DevDependencies:
- **Build and Testing**:
  - Angular CLI
  - TypeScript
  - Karma (Test Runner)
  - Jasmine (Testing Framework)
  - Karma Chrome Launcher
  - Karma Coverage

#### Dependencies:
- **Core**:
  - Angular Animations
  - Angular CDK
  - Angular Common
  - Angular Compiler
  - Angular Core
  - Angular Forms
  - Angular Material
  - Angular Platform Browser
  - Angular Platform Server
  - Angular Router
  - Angular SSR
- **Third-Party Libraries**:
  - ApexCharts
  - Bootstrap
  - Express
  - jQuery
  - ng-apexcharts
  - RxJS
  - Zone.js

---

## Application UI

### Admin:
#### ![Welcome Page](Images/Application%20UI/Admin/welcomepage.png)
#### ![LogIn Page](Images/Application%20UI/Admin/login%20page.png)
#### ![Admin Dashboard](Images/Application%20UI/Admin/Admin%20dashboard.png)
----
### Manager:
#### ![Manager - I](Images/Application%20UI/Manager/1%20Mnagaer.png)
#### ![Manager - II](Images/Application%20UI/Manager/2%20manager.png)
#### ![Manager - III](Images/Application%20UI/Manager/3%20manager.png)
#### ![Manager - IV](Images/Application%20UI/Manager/4%20manager.png)
----
### Employee:
#### ![Employee - I](Images/Application%20UI/employee/Screenshot%20from%202024-05-24%2013-08-59.png)
#### ![Employee - II](Images/Application%20UI/employee/Screenshot%20from%202024-05-24%2013-09-03.png)
#### ![Employee - III](Images/Application%20UI/employee/Screenshot%20from%202024-05-24%2013-09-49.png)
---


### Created by:
- MT2023153 - Arjun Gangani [Arjun.Gangani@iiitb.ac.in](mailto:Arjun.Gangani@iiitb.ac.in)
- MT2023050 - Vraj Naik [Vraj.Naik@iiitb.ac.in](mailto:Vraj.Naik@iiitb.ac.in)

### Guided by:

- Prof. B. Thangaraju [B.Thangaraju@iiitb.ac.in](mailto:B.Thangaraju@iiitb.ac.in)

### Assisted by:
- MT2019075 - Samaksh Dingra [Samaksh.Dhingra@iiitb.ac.in](mailto:Samakash.Dhingra@iiitb.ac.in)
---


For more details on the backend repository, refer to the [Backend Repository](https://github.com/ARJUN1220/SPE_backend).
