Task Management System

This is a Node.js-based task management system that includes user management, task management, tagging, commenting, and notification features. It uses MySQL as the database, Sequelize as the ORM, and JWT for authentication.

Features

User Management

User registration and login with JWT authentication.

User roles: Admin and Regular User.

Only Admins can create other Admins.

Task Management

Users can create tasks with a title, description, due date, and status (e.g., To-Do, In Progress, Completed).

Users can assign tasks to themselves or others.

Users can update the status of their own tasks.

Admins can update the status of any task.

Tagging System

Users can add tags to tasks (e.g., "Urgent", "Bug", "Feature").

Users can filter tasks by tags.

Commenting System

Users can add comments to tasks.

Users can edit or delete their own comments.

Admins can delete any comment.

Notifications

Notify users when they are assigned a task or when the status of a task they are involved in is updated.

Real-time notifications (optional, using WebSockets).

Validation

Payload validation for all endpoints (e.g., valid email format, required fields).

Pagination & Sorting

Implement pagination and sorting for tasks (e.g., sort by due date, filter by status).
