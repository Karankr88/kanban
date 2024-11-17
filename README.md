# Kanban Board Application

A fully interactive Kanban board built with ReactJS that fetches ticket data from a provided API. The board dynamically adjusts based on the selected grouping and sorting options. It allows users to visualize, filter, and sort tickets by different criteria, including status, assigned user, priority, and title.

## Demo

You can view the live demo of the project at the following link:

[Live Demo Link](https://kanban-blond-two.vercel.app/)


## Features

- **Dynamic Grouping**: Group tickets based on:
  - **Status**: Group tickets according to their current status (e.g., Open, In Progress, Closed).
  - **User**: Group tickets based on the assigned user.
  - **Priority**: Group tickets based on priority level (Urgent, High, Medium, Low, No Priority).
  
- **Sorting Options**: Sort the displayed tickets by:
  - **Priority**: Display tickets in descending order based on their priority.
  - **Title**: Sort tickets in ascending order based on their title.

- **Responsive Design**: The application is designed to be mobile and tablet responsive, ensuring the Kanban board works seamlessly across various screen sizes.

- **Persistence**: The board maintains the user's view state even after page reloads, ensuring continuity of their settings.

## Priority Levels

Tickets can have the following priority levels:

- **Urgent (Priority 4)**: High urgency.
- **High (Priority 3)**: Important but not urgent.
- **Medium (Priority 2)**: Moderate priority.
- **Low (Priority 1)**: Low priority.
- **No Priority (Priority 0)**: No defined priority.

## Technologies Used

- **ReactJS**: JavaScript library for building user interfaces.
- **Pure CSS**: Custom styling (no external CSS libraries like Bootstrap or Tailwind).
- **Local Storage**: Used to persist the user's view state even after page reload.

## API Integration

The application interacts with the following API endpoint to fetch the ticket data:

