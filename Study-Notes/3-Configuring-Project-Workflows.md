# Configuring Project Workflows

## workflow basics
status - where
transition - how 
assignee  - who
resolution - why

possible to have global transitions (Allow any status to change to any other status)

status
    to do - blue
    done - green
    in process - yellow

Custom workflows

conditions
validators
automated functions
custom trsition screens for input

jir admins only people to edit workflows. 
project admins have limited 


BOARDS

tied to workflows (Adding bloced to a board will udpate the workflow)
configuring boards:
    to add status to board

| Jira admin | Proj admin + board admin | board admin | Proj admin | task |
|--          |--                        |--           |--          |      |
| *          |*                         |*            |            |Add columns to bard and map status |
| *          |*                         |             |            | Add new status to board |
| *          |*                         |*            |            | switch ti simplified workflow |



Project Admins CAN:
edit workflow in there project (if unshared)
create update and delete transitions
add existing status to worflow
delete status  taht araent used bt their projects issues


project admins CANT
edit shared workflows
edit defauly syste workflows
select / update transition screen
edit transition proerties , conditions, validators or functions


possible to edit project admin to allow worflow customizations

create a status when
    hand off to new person
    peice of work stays in status for long time

* try not to create lots of status

Advanced workflow configuraiton

Condition:
    Must be meet before tranistion is available
Validation
    checks input is valid during transition
Trigger
    automates transition by even in devtools
post function
    automates actions after transtion



The transition issue permissions lmits who can use any workflow transction. 
for a team to use the workflow ensure they ahve permisions

Testing workflows
go through each tatus and transtion
check screens
check conditions
confirm no valudations alerts

Troubleshoot workflow

view in workflow editor
check statuses and trasitions
look at conditions.validators, post functions
check permissions and roles

talk to jira admins









































