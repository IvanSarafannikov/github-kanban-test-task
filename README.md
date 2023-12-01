# Github Kanban Board

Implement a simple kanban board service with backend and frontend.

## Requirements
1. User should enter unique workspace ID in the input on top of the page and press "Connect". For example: `600796a8-9e79-4894-84b4-def927689c57`.
2. User should also be able to create a new workspace and have its ID automatically put in the input.
3. App loads tasks from the provided workspace
4. App contains 3 columns:
- ToDo
- In Progress
- Done

4. User should be able to drag-n-drop between the columns and change the order of tasks.
5. User should be able to create new tasks.
6. All changes should be sent to the server and stored in the database.
7. Each workspace should have separate task lists.

## Technologies

You should use exactly the listed technologies or one of them if it is allowed:

### Frontend
- React 18 with hooks, no classes
- Typescript
- UI library (on your choice):
  - Ant Design
  - React-Bootstrap
  - Semantic UI
  - Blueprint UI
- State manager (on your choice):
  - Redux (or Redux-Toolkit)
  - MobX
  - Recoil
- Testing (on your choice):
  - React Testing Library
  - Cypress
- any other library you need

### Backend
- NodeJS, any LTS version that isn't EOL
- Typescript
- Express or NestJS
- PostgreSQL or MongoDB

## Assessment

What will we assess:
- workability: how your application works
- projects structure: how you structure your files
- code quality: how you write clean, readable code (feel free to install and use ESLint and Prettier)
- knowledge of React and its ecosystem: how you compose and use libraries together
- testing: how you can test your code

## Mockups

![Design](./design.png)

## How to complete the task
- create a new public repo on Github (do **NOT** fork this repository)
- develop the application according to the requirements
- send us the link to your repo
