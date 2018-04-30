# 2: Getting Started with Projects
### Listen
JIRA has multiple versions
- Jira Software
    - Used for software delivery
- Jira Service Desk
    - Used for service or operations help desk
- Jira Core
    - Used for business processes (HR onboarding etc)

Course and exam is based on the Jira Software

#### Project Templates:
When creating a new project you will have the following based on which version of Jira you have installed:
- Jira Software
    - Scrum software development
    - Kanban software development
    - Basic software development
- Jira Service Desk
    - Basic
    - IT Service Desk
    - Customer service
- Jira Core
    - Project management
    - Task management
    - Process management


#### Default Issue Types for Projects:
Depending on which template you use, different issue types will be available

Each issue can act differently (have different workflows, fields etc)

- Scrum & Kanban:
    - Bug, Task, sub-task, story, epic
- Basic Software development:
    - Bug, task, sub-task, *improvement, new feature*, epic
- Business (Core):
    - Task, sub-task

Creating issue types:
- only create when needed and with a good reason
    - if internal requests are delt differently to internal

Workflow
- status
    - position of issue in workflow (in progress, done, blocked)
- transition
    - how status moves from status to status (relationships of status)
- Assignee
    -   help define who works on what depending on status(?)
- Resolution
    - why an item is not in flight anymore (open to closed)

## permissions

TO create a new project
    JIra admiinsitrator
    project acce

When you create a new project:
- project lead
    - manages the project
- default assignee (
    - by default set to unassigned, but can be set to a specific person)
- Project administraotr
    - edit project details
    - assign project members
    - limit editing of peoject workflow / screens
    - jira-administrators are included by default

## Project Categories:
Projects can only belong to 1 category

good for limiting access to defauly groups

## Schemes
is a container for configuration items (8 in total)
only jira-administrators can create / modify schemas and assiciate them to projects
assign schemes to projectsz\

Unique Schemes:
Changes to schemese will effect ONLY the project
    - Issue Type
    - Workflow
    - Issue Type Schreem
Shared Schemes:
Changes to these schemese will effect ALL projects
    - Permissions
    - Notification
    - Priority
    - Field Configuration

The 8th scheme has to be created manually by JIra-Administrator
Installed:
    - Issue Security 


### Implications of using project templates
Customiing project templates can cause you to create lots of unquie schemes, which has overhead and makes standards hard. 

Sharing Schemese between projects:
Schemese can be shared between projects
Sharing schmese is good! saves work and keeps things to standards. 


#### creating projects with shared configs



# Labs
Only jira admins can update a project key