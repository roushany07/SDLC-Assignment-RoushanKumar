# Smart-Attend Mobile Attendance System

## Course

SDLC & DevOps Fundamentals

## Role

Junior Project Manager

---

# Project Overview

Smart-Attend is a mobile-based attendance management application developed to simplify and automate the process of recording student attendance in classrooms. The system uses **Geo-fencing technology**, which allows the application to detect when a student enters a predefined classroom boundary. Once the student enters the designated area, the system automatically marks the student's attendance.

Initially, the system relied only on location-based verification. However, during the development process, the university administration introduced an additional requirement: **Biometric Face ID verification must be integrated to prevent proxy attendance**. Proxy attendance occurs when one student attempts to mark attendance for another student who is not physically present in the classroom.

With the addition of this feature, the Smart-Attend system verifies two important factors:

• The **physical location** of the student using Geo-fencing
• The **identity of the student** using Face ID authentication

To manage these continuous improvements and updates efficiently, the project adopts modern development practices such as **CI/CD (Continuous Integration and Continuous Deployment)**.

---

# Agile Development and Sprint Updates

The Smart-Attend system follows an **Agile development approach**, specifically the **Scrum framework**. In Agile development, software is built and improved in short development cycles known as **Sprints**.

Each sprint typically lasts two weeks and focuses on delivering specific features or improvements to the system. For example:

Sprint 1 focuses on developing the **Minimum Viable Product (MVP)** which includes basic user interface, student login functionality, and Geo-fencing based attendance detection.

Sprint 2 focuses on integrating **Biometric Face ID verification**, improving system security, and refining the teacher dashboard.

Because the system is updated after every sprint, an efficient mechanism is required to integrate, test, and deliver these updates quickly. This is where **CI/CD plays a critical role**.

---

# Continuous Integration (CI)

Continuous Integration is a development practice in which developers frequently merge their code changes into a shared repository such as GitHub.

Whenever developers push new code changes:

• The system automatically builds the application
• Automated tests are executed to check for errors
• Integration issues between different modules are detected early

This process ensures that newly developed features from each sprint are continuously tested and validated. It helps developers identify bugs and conflicts early in the development cycle instead of discovering them at the end of the project.

Continuous Integration improves collaboration among developers and ensures that the software remains stable even as new features are added.

---

# Continuous Deployment (CD)

Continuous Deployment is the process of automatically releasing tested updates to the end users after the system successfully passes all required checks and tests.

In the Smart-Attend system, Continuous Deployment ensures that:

• New features developed during each sprint are quickly delivered to students
• Bug fixes and performance improvements are deployed without delay
• Users always have access to the latest version of the application

Instead of manually releasing updates, the deployment process is automated. This reduces the chances of human error and significantly speeds up the release process.

---

# How CI/CD Helps Deliver Sprint Updates to Students

The combination of Continuous Integration and Continuous Deployment allows the Smart-Attend system to deliver sprint updates efficiently.

The typical process works as follows:

1. Developers complete new features or improvements during a sprint.
2. The updated code is pushed to the GitHub repository.
3. Automated build and testing processes are triggered.
4. If the system passes all tests, the update is automatically deployed.
5. Students receive the updated application version containing the latest features and improvements.

This automated pipeline ensures that sprint updates reach users quickly and reliably.

---

# Advantages of Using CI/CD

Implementing CI/CD provides several important benefits for the Smart-Attend system:

• Faster delivery of new features developed during sprints
• Early detection of software bugs and integration issues
• Automated testing and deployment processes
• Reduced manual effort in releasing updates
• Improved reliability and stability of the application
• Continuous improvement of the system for students and faculty

These benefits make CI/CD an essential practice for modern software development projects.

---

# Conclusion

CI/CD plays a vital role in supporting Agile development for the Smart-Attend application. By automating the integration, testing, and deployment processes, CI/CD ensures that sprint updates can be delivered efficiently and automatically to students.

This approach improves development speed, reduces errors, and ensures that the application remains secure, reliable, and continuously updated with new features and improvements.
