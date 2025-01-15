# Event Management System

This repository contains a web-based Event Management System designed to facilitate the creation, management, and participation in various events.

## Features

- **Event Creation**: Organizers can create events with detailed information, including date, time, location, and description.
- **User Registration**: Users can register for events and receive confirmations.
- **Event Listing**: Browse and search for upcoming events.
- **Responsive Design**: Accessible on various devices with an intuitive user interface.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask Framework)
- **Database**: SQLite
- **Containerization**: Docker

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/get-started) installed on your machine.

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/prashant-1134/Event_System.git
   cd Event_System
   ```


2. **Build and Run with Docker**:

```bash
docker-compose up --build
```

3. **Access the Application**:

Once the containers are up and running, you can access the application at 
```
http://localhost:5000.
```

## Project Structure
```
Event_System/
├── database/
│   └── event_system.db       ( SQLite database file)
├── static/
│   ├── css/
│   ├── js/
│   └── images/
├── templates/
│   ├── index.html
│   ├── event_detail.html
│   └── ...
├── app.py                    ( Main Flask application)
├── Dockerfile                ( Docker image configuration)
├── docker-compose.yml        ( Docker Compose configuration)
└── requirements.txt          ( Python dependencies)
```
## Usage
### Create an Event:
Navigate to the "Create Event" page, fill in the event details, and submit.
### Register for an Event: 
Browse the list of events, select an event, and complete the registration form.
### View Event Details:
Click on an event to view detailed information.

 Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.


