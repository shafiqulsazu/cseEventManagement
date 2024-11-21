<p align="center">
  <img src="HSTU_Logo.png" alt="HSTU Logo" width="250" height="300">
</p>

<h3 align="center">
  Course Title: Software Engineering
</h3>

<h3 align="center">
  Course Code: CSE 305
</h3>

<h3 align="center">
  Hajee Mohammad Danesh Science and Technology University,Dinajpur-5200.
</h3>
<br><br>


<p align="center">
  <img src="Event.png" alt="Event Logo" width="250" height="250">
</p>

<br><br>

<h1 align="center">CSE Department Event Management System</h1>


The proposed system is a **CSE Department Event Management System (CDEMS)** that allows the administration, department, and students to efficiently organize, manage, and participate in department-related events such as workshops, seminars, sports, or cultural fests. The system will automate various processes, including event registration, notifications, schedules, feedback collection, and result announcements. This project idea can be developed step by step by applying the **Software Development Life Cycle (SDLC)** to ensure a high-quality system.


<h1 align="center">SDLC phases apply to my CSE Department Event Management System</h1>

## Planning
  
**Objective**: Define the scope and purpose of the idea.

**Activities**:
- Identify the need for the project (e.g., ease of managing departmental events)
- Determine the target users (students, department, organizers).
- Outline key goals, such as organizing workshops, seminars, fests, and sports effectively.

## Requirements Analysis

**Objective**: Identify the expected features and constraints of the system.

**Activities**:
- List functional requirements (e.g., event scheduling, participant registration).
- Document non-functional requirements (e.g., user-friendly interface, file-based storage).
- Analyze potential challenges (e.g., limited resources, user adoption).

## Design

**Objective**: Visualize the structure and functionality of the system.

**Activities**:
- Sketch high-level mockups for the user interface (event calendar, registration forms).
- Plan how data will be structured and stored in files.
- Create diagrams to map workflows like event creation and participant registration.

## Conceptualization (In place of Implementation)

**Objective**: Develop the theoretical framework of the system.

**Activities**:
- Describe how the system would function in various scenarios.
- Specify the roles of users (admins vs. participants).
- Draft guidelines for how events would be managed and displayed.

## Review and Validation

**Objective**: Validate the project idea with stakeholders.

**Activities**:
- Present the idea to peers, faculty, or department heads.
- Gather feedback on the feasibility and usefulness of the proposed system.
- Revise the idea based on suggestions and feedback.

## Documentation

**Objective**: Create comprehensive documentation of the project idea.

**Activities**:
- Write a project report detailing the purpose, features, and expected benefits.
- Include diagrams, mockups, and descriptions of workflows.
- Document potential future extensions or implementation plans.

## Class Diagram
The Class Diagram for the **CSE Department Event Management System** is designed to represent the various entities involved in managing department events efficiently. It illustrates the different classes and their relationships, providing an abstraction of the system's core components.
<br>
<p align="center">
  <img src="class.png" alt="CDEMS class Diagram" height="400">
</p>

## Test Cases Sample

|Test ID |         Test Condition           |     Test Steps       |      Test Input             |    Test outcome        |    Actual Outcome    |   Status    |
|        |----------------------------------|----------------------|-----------------------------|------------------------|----------------------|-------------|
|  1     | With valid user ID & password if | 1.Enter username     |  Username:shafiqul          |    Login successful    |   Login successful   |    Pass     |
|        | login able                       | 2.Enter password     |  Password:hstushafiqul      |                        |                      |             |
|        |                                  | 3.Login              |                             |                        |                      |             |
|--------|----------------------------------|----------------------|-----------------------------|------------------------|----------------------|-------------|
|  2     | With invalid user Id & password  | 1.Enter username     |  Username:sazu              |  Login unsuccessful    |  Login unsuccessful  |    Pass     |
|        |                                  | 2.Enter password     |  Password:hstusazu          |                        |                      |             |
|        |                                  | 3.Login              |                             |                        |                      |             |
|--------|----------------------------------|----------------------|-----------------------------|------------------------|----------------------|-------------|
<br>
