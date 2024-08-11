### Real-Time-Collaboration-Tool
## Project Overview

This project is a web-based document management and collaborative editing tool that enables real-time collaboration among users. The application is divided into two main components: the backend, which handles document management and real-time updates, and the frontend, which provides an intuitive interface for users to create, edit, and collaborate on documents.

## Backend

- **Strapi** is used as the content management system (CMS) to manage documents.
- **APIs** are created for document creation, editing, and sharing, enabling seamless interaction with the frontend.
- A **WebSocket server** is set up to facilitate real-time collaboration, ensuring that changes made by one user are instantly reflected to all collaborators.

## Frontend

- **React** is utilized to develop a robust document editor with a focus on responsiveness and user experience.
- **Tailwind CSS** is employed for styling, providing a modern and consistent design.
- **Real-time collaborative editing** features are implemented, allowing multiple users to work on the same document simultaneously.
- **Redux** is used for state management, ensuring efficient handling of real-time updates and maintaining synchronization across all users' views.
