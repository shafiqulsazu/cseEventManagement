<p align="center">
  <img src="HSTU_Logo.png" alt="HSTU Logo" width="250" height="300">
</p>

<h3 align="center">
  Hajee Mohammad Danesh Science and Technology University,Dinajpur-5200.
</h3>
<h3 align="center">
Project Name: CSE Department Event Management System
</h3>

<h3 align="center">
  Course Title: Software Engineering
</h3>

<h3 align="center">
  Course Code: CSE 305
</h3>
<br>
<h1 align="center">Submitted By</h1>

 <p align="center">Md. Shafiqul Islam Sazu<br>Student ID: 2102035<br>Level: 3 Semester: I<br>Department of Computer Science and Engineering</p>
 <br>

<h1 align="center">Submitted To</h1>

 <p align="center">Pankaj Bhowmik<br>Lecturer<br>Department of Computer Science and Engineering</p>


<br><br><br>


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
  <img src="Class.png" alt="CDEMS class Diagram" height="400">
</p>
<br>

## Test Cases Samples:

## Event Creation

|Test ID | Test Case Description                       |  Expected Outcome                                       |  Actual Outcome                          |  Status            |
|--------|---------------------------------------------|---------------------------------------------------------|------------------------------------------|--------------------|
|  1     |	Create a new event with valid details      | Event is successfully created and saved to the system   | Create Event Successfully                |   Pass             |
|  2     |Create an event with missing mandatory fields|System shows an error message for missing required fields| Event created Failed                     |   Pass             |
<br>

## User Management

|Test ID |         Test Condition                    |     Test Steps                                |      Test Input                          |    Test outcome        |    Actual Outcome    |   Status    |
|--------|-------------------------------------------|-----------------------------------------------|------------------------------------------|------------------------|----------------------|-------------|
|  3     |With valid user ID & password if login able|1.Enter username<br>2.Enter password<br>3.Login|Username:shafiqul<br>Password:hstushafiqul|    Login successful    |   Login successful   |    Pass     |
|        |                                           |                                               |                                          |                        |                      |             |
|  4     | With invalid user Id & password           |1.Enter username<br>2.Enter password<br>3.Login|Username:sazu<br>Password:hstusazu        |  Login unsuccessful    |  Login unsuccessful  |    Pass     |


<br>

## Schedule Management

|Test ID | Test Case Description                           |  Expected Outcome                                      |   Actual Outcome                           |   Status            |
|--------|-------------------------------------------------|--------------------------------------------------------|--------------------------------------------|---------------------|
|  5     |Create a schedule for an event with valid details|Schedule is successfully created and linked to the event|    Schedule successfully created           |   Pass              |
|  6     |Create a schedule with overlapping time slots    |System shows an error for overlapping schedules         |        Show an error                       |   Pass              |
|  7     |	Update an existing schedule                    |		Schedule updates are saved successfully             |         Schedule Updated                   |   Pass              |
<br>

## Participant Management

|Test ID | Test Case Description                           |  Expected Outcome                                 |    Actual Outcome                  |   Status         |
|--------|-------------------------------------------------|---------------------------------------------------|------------------------------------|------------------|
|  8     |Add participants to an event                     | Participants are added successfully to the event  |      Participants added            |   Pass           |
|  9     |	Remove participants from an event              | Participants are removed successfully             |      Participants Removed          |   Pass           |
|  10    |	Attempt to add participants with invalid data  |Shows an error message for invalid participant data|      Invalid Data                  |   Pass           |
<br>

##  System Validation and Security

|Test ID | Test Case Description                          |  Expected Outcome                                   |  Actual Outcome                      |   Status        |
|--------|------------------------------------------------|-----------------------------------------------------|--------------------------------------|-----------------|
|  11    |	Test access control for organizer-only actions|Non-organizer users cannot perform restricted actions|        Access Denied                 |    Pass         |
|  12    | Validate input fields against SQL injection    | System prevents any malicious SQL injection attempts|   You have been blocked              |    Pass         |
<br>
 

## Requirement Analysis

**Activities**: Gather and analyze requirements, define system features.<br>**Duration**: 1 week<br>**Dependencies**: None<br>

## System Design

**Activities**: Design class diagrams, flowcharts, and database schema.<br>**Duration**: 2 weeks<br>**Dependencies**: Requirement Analysis<br>

## Conceptualization (Coding)

**Activities**: Code event management features, user management, schedule management, etc.<br>**Duration**: 4 weeks<br>**Dependencies**: System Design<br>

## Testing

**Activities**: Test individual components, perform integration testing.<br>**Duration**: 2 weeks<br>**Dependencies**: Implementation<br>

## Deployment

**Activities**: Deploy the system on servers, configure the environment.<br>**Duration**: 1 week<br>**Dependencies**: Testing<br>

## Maintenance

**Activities**: Fix bugs, add new features as necessary.<br>**Duration**: Ongoing<br>**Dependencies**: Deployment<br><br>

## Gantt Chart Representation

[Gantt chart](https://www.gantt.com/) for my **CSE Department Event Management System** based on my **Software Development Life Cycle (SDLC)**:

|          Activity                  |   Duration      |        Dependencies              |
|------------------------------------|-----------------|----------------------------------|
| Requirement Analysis               |    1 week       |   None                           |
| System Design                      |    2 weeks      |   Requirement Analysis           |
| Conceptualization                  |    4 weeks      |   System Design                  |
| Testing                            |    2 weeks      |   Conceptualization              |
| Deployment                         |    1 week       |   Testing                        |
| Maintainance                       |    Ongoing      |   Deployment                     |
<br>



|Activity              |Week 1|Week 2 Week 3|Week 4 Week 5 Week 6 Week 7|Week 8 Week 9|Week 10|Week N              |
|----------------------|------|-------------|---------------------------|-------------|-------|--------------------|
|Requirement Analysis  |██████|             |                           |             |       |                    |
|System Design         |      |██████████   |                           |             |       |                    |
|Conceptualization     |      |             |██████████████             |             |       |                    |
|Testing               |      |             |                           |██████████   |       |                    |
|Deployment            |      |             |                           |             |██████ |                    |
|Maintenance           |      |             |                           |             |       |████████████████████|(Ongoing)
<br>

## Conclusion

The **CSE Department Event Management System** is designed to streamline the process of organizing and managing departmental events efficiently. With its robust features for handling events, schedules, participants, and resources, the system ensures that every aspect of event planning and execution is seamlessly integrated.

This project aims to minimize manual effort, enhance collaboration, and provide a centralized platform for managing events of varying scales. By following the outlined development phases and utilizing the provided resources, the system can be further extended and customized to meet specific departmental needs.

We hope this project serves as a valuable tool for the department and contributes to the success of academic and extracurricular events. For further enhancements or issues, feel free to refer to the documentation or raise queries in the project repository.
<br><br><br>

 

