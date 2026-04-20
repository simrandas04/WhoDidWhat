# Project Description: WhoDidWhat – Simplified Issue Tracking System

**WhoDidWhat** is a lightweight, web-based issue tracking system inspired by Jira, designed with a strong emphasis on **clarity, traceability, and ease of use**. The system enables users to create, manage, assign, and monitor tickets while maintaining a clear and human-readable history of all actions performed on each ticket.

Unlike traditional issue tracking tools that often introduce complexity through extensive configurations and technical logs, WhoDidWhat focuses on delivering a **minimal, intuitive, and transparent workflow experience**. The primary goal is to make ticket ownership, transitions, and lifecycle events easily understandable at a glance.

## Key Features

* **Ticket Management:**
  Users can create, update, and manage tickets with essential attributes such as title, status, assignee, and timestamps.

* **Assignment Tracking:**
  The system supports assigning and reassigning tickets while clearly recording *who assigned the ticket to whom* and when the action occurred.

* **Human-Readable History:**
  Each ticket maintains a structured history that logs actions in a narrative format (e.g., “Simran assigned ticket to Rahul”), improving readability over traditional system logs.

* **Timeline Visualization:**
  A chronological timeline view allows users to trace the complete lifecycle of a ticket, from creation to completion.

* **Global Activity Feed:**
  All system-wide actions are captured in a centralized activity feed, providing visibility into overall team activity.

* **Smart Assignment Suggestion:**
  The system includes a simple intelligent mechanism to suggest the most suitable assignee based on current workload distribution.

* **Dashboard Analytics:**
  A dashboard provides key metrics such as total tickets, in-progress tasks, and completed tickets, enabling quick performance insights.

* **Blame-Free Tracking:**
  The system emphasizes contribution tracking rather than fault identification, focusing on actions and participation instead of errors.

## System Architecture

The application follows a lightweight architecture:

* **Frontend:** React.js (functional components with hooks)
* **Backend:** JSON Server (mock REST API)
* **Data Storage:** JSON-based structure for simplicity and transparency

This architecture ensures fast performance, ease of development, and maintainability, making the system suitable for educational purposes and small team environments.

## Conclusion

WhoDidWhat demonstrates how an issue tracking system can be redesigned to prioritize **usability and transparency over complexity**. By combining clear workflows, readable history tracking, and lightweight architecture, the system provides an efficient and user-friendly alternative to traditional tools like Jira.

