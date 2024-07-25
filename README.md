# IT Helpdesk Ticketing System

## Project Description
A simple IT Helpdesk Ticketing System to manage support requests. This system allows users to create tickets, assigns them to support agents, and tracks their status until resolution.

## Features
- Ticket creation
- Ticket assignment
- Status updates
- Retrieve open tickets

## Database Schema
- Users: Stores user information
- SupportAgents: Stores support agent information
- Tickets: Stores ticket information and tracks status

## Setup Instructions
1. Set up a MySQL database and create the tables using the provided schema.
2. Update the database connection details in the Python scripts.
3. Run the Python scripts to interact with the ticketing system.
4. (Optional) Set up the Flask application for a web interface.

## Usage
- Create a ticket by calling the `create_ticket` function.
- Assign a ticket to an agent by calling the `assign_ticket` function.
- Update ticket status by calling the `update_ticket_status` function.
- Retrieve open tickets by calling the `get_open_tickets` function.

## Future Improvements
- Add authentication and user roles.
- Implement a more sophisticated ticket priority and SLA management.
- Integrate email notifications for ticket updates.
