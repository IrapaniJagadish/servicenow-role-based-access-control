# Optimizing User, Group, and Role Management with Access Control and Workflows

## Project Overview

This project demonstrates the implementation of a Role-Based Access Control (RBAC) system in ServiceNow to efficiently manage users, groups, roles, and project tasks. The solution ensures secure access to project records by assigning different permissions to Project Managers and Team Members. Access Control Lists (ACLs) and Flow Designer workflows are used to automate task assignment and maintain accountability throughout the project lifecycle.



## Objectives

- Create and manage users, groups, and roles.
- Implement Role-Based Access Control (RBAC).
- Configure Access Control Lists (ACLs).
- Restrict unauthorized access.
- Automate task assignment using Flow Designer.
- Allow Team Members to update only permitted fields.
- Validate role-based access.



## Technologies Used

- ServiceNow
- Users, Groups & Roles Management
- Access Control Lists (ACLs)
- Flow Designer
- Data Management
- Import Sets
- Update Sets



## Features

### User Management
- Created Project Manager (Alice)
- Created Team Member (Bob)

### Role Management
- Custom Project Manager role
- Custom Team Member role

### Group Management
- Project Team group

### Task Management
- Custom Project Task table
- Task assignment
- Status tracking
- Work Notes
- Priority management

### Access Control

**Project Manager**
- Create Tasks
- Edit Tasks
- Delete Tasks
- Assign Tasks

**Team Member**
- View assigned tasks only
- Update Status
- Add Work Notes
- Cannot create, delete or modify restricted fields

### Workflow Automation

Flow Designer automatically:
- Sends notification when a task is assigned.
- Tracks status changes.
- Notifies the Project Manager when a task is completed.



## Testing

### Project Manager
- Create, Edit, Delete and Assign tasks.
- View all project tasks.

### Team Member
- View assigned tasks only.
- Update Status.
- Add Work Notes.


## Future Enhancements

- Email Notifications
- Dashboards
- SLA Management
- Approval Workflow
- Reports & Analytics
