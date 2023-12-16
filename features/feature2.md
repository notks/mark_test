# Task Manager Integration

## Overview

The Task Manager Integration feature streamlines collaboration by allowing users to link tasks directly to the app. This README provides a quick guide on setting up and using the integration.

## Installation

To enable Task Manager Integration, follow these steps:

1. Navigate to the app settings.
2. Find the "Integrations" section.
3. Locate "Task Manager" and click "Connect."

## Supported Task Managers

- [ ] Trello
- [ ] Asana
- [ ] Jira

## Linking Tasks

Once the integration is set up, linking tasks is straightforward:

1. Open the app and navigate to the project.
2. Click on the task you want to link.
3. In the task details, find the "Link to App" option.
4. Select the app project where you want to link the task.

## Viewing Linked Tasks

Easily track linked tasks within the app:

1. Access the project where the task is linked.
2. The linked task appears in a dedicated "Linked Tasks" section.

## Unlinking Tasks

If needed, unlink tasks by following these steps:

1. Open the app and navigate to the project.
2. Find the linked task in the "Linked Tasks" section.
3. Click on the task and choose "Unlink."

## Example API Usage

Developers can programmatically interact with the Task Manager Integration using the API:

```bash
# Link a task
POST /api/tasks/link
{
  "app_project_id": "123",
  "task_manager": "trello",
  "task_id": "trello-task-456"
}

# Unlink a task
DELETE /api/tasks/unlink
{
  "app_project_id": "123",
  "linked_task_id": "trello-task-456"
}
