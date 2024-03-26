# JDiscord

JDiscord is a simple chat application built using Java. It allows multiple clients to connect to a server and exchange messages in real time.

## Features

- Real-time messaging: Users can send and receive messages in real time.
- User join/quit notifications: When a user joins or quits the chat, a notification is sent to all connected clients.

## Prerequisites

To run this project, you will need:

- Java 8 or higher
- IntelliJ IDEA or any other Java IDE

## Deployment

To deploy this application, follow these steps:

1. Clone the repository: `git clone https://github.com/fancyvanilla/JDiscord.git`
2. Navigate to the project directory: `cd JDiscord`
3. Compile the project: `javac src/*.java`
4. Run the server: `java src/Server`
5. In a new terminal window, run the client: `java src/Client`

You can run multiple clients by repeating step 5 in different terminal windows.

## Testing

To test the application, simply run the client and server applications. You should be able to send messages from each client and see them appear in all other clients.

## Built With

- Java - The programming language used
- IntelliJ IDEA - The IDE used

