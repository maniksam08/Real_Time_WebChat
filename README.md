# Real-Time Web Chat (Java)

A real-time web chat application built with **Java and the Spring Framework**. Messages are delivered instantly between connected users over **WebSockets**. The project focuses on backend functionality and real-time communication rather than frontend polish.

## Features

- Real-time, bi-directional messaging over WebSockets
- Multiple users chatting at the same time
- Spring MVC backend serving the chat UI
- Lightweight HTML/CSS frontend

## Tech Stack

| Layer    | Technology                          |
| -------- | ----------------------------------- |
| Backend  | Java, Spring Framework (Spring MVC) |
| Realtime | WebSockets                          |
| Frontend | HTML, CSS                           |
| Build    | Maven 

## Project Structure

```
Real_Time_web_Java/
├── src/            # Spring application source
├── .gitattributes
└── Readme.md
```
## Images
<img width="1758" height="785" alt="Screenshot 2026-10-03 034951" src="https://github.com/user-attachments/assets/008e3349-ab75-4505-b9d6-c63b84f61fe3" />
<img width="1916" height="936" alt="Screenshot 2026-10-03 035303" src="https://github.com/user-attachments/assets/07f2c639-9d3a-40ae-a031-2583bc5172e8" />

## Getting Started

### Prerequisites

- JDK 21 
- Maven 3.8+ 

### Run locally

```bash
# 1. Clone the repository
git clone https://github.com/maniksam08/Real_Time_web_Java.git
cd Real_Time_web_Java/demo

# 2. Build and run
./mvnw spring-boot:run      # or: mvn spring-boot:run / ./gradlew bootRun
```

Then open **http://localhost:8080** in two or more browser tabs, enter a name, and start chatting.

## How It Works

1. The browser loads the chat page served by a Spring MVC controller.
2. The client opens a WebSocket connection to the server.
3. When a user sends a message, the server receives it and broadcasts it to all connected clients.
4. Each client renders incoming messages immediately, with no page refresh.

## Roadmap

- [ ] Private / one-to-one messages
- [ ] Persistent message history (database)
      
## Contributing

Issues and pull requests are welcome. Fork the repo, create a feature branch, and open a PR.

## Author

**Pratham Arora** — [GitHub](https://github.com/maniksam08)
