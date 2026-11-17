# WebLab7
Event Registration API is a Spring Boot application that provides REST endpoints for managing events. Each event contains an ID, a title, and a location. The application stores event data in memory, so changes are lost when the application restarts. The server assigns unique IDs to new events.

To run the application, open the project in IntelliJ IDEA and start the main Spring Boot application class. The server runs on http://localhost:8080 by default.

The API supports several HTTP operations. GET /api/events returns all events, and GET /api/events/{id} returns an event by ID. The optional title parameter allows users to search for events by title. POST /api/events creates a new event using JSON data. PUT /api/events/{id} updates an existing event, while DELETE /api/events/{id} removes it.

You can test all endpoints using Postman. The application returns suitable HTTP status codes for successful requests, invalid input, and events that do not exist.
