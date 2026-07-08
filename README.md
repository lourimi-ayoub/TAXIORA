# TAXIORA

> Real-time taxi booking simulation for passengers, drivers, and administrators.

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![React Native](https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactnative.dev/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)](https://socket.io/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)

## 📖 Overview

TAXIORA is a real-time taxi booking simulation platform designed to model the complete ride lifecycle across passenger, driver, and administrator experiences.

The project focuses on the operational flow of a modern ride-hailing system: request creation, live coordination, dispatching decisions, and end-to-end simulation of service behavior. It is well suited for research, demonstration, and scenario-based analysis of taxi mobility workflows.

## ✨ Features

- Real-time taxi booking simulation.
- Passenger, driver, and administrator interactions within a shared system.
- Ride lifecycle management from request to completion.
- Live communication and status updates.
- Dispatching and driver-assignment flows.
- Map-oriented experience for tracking and simulation.
- AI-assisted decision support for driver selection.
- Web and mobile experiences for different user roles.

## 🛠 Tech Stack

| Layer          | Technologies                                                           |
| -------------- | ---------------------------------------------------------------------- |
| Frontend       | React, React Native, Expo, Vite, PrimeReact, Leaflet, Mapbox, Recharts |
| Backend        | Node.js, Express, Socket.IO, Mongoose                                  |
| Database       | MongoDB                                                                |
| Authentication | JSON Web Tokens, bcryptjs, secure token storage                        |
| APIs           | Socket.IO, routing and mapping services, external fetch integrations   |
| AI             | AI-assisted driver selection and dispatch support                      |
| Deployment     | Docker, Docker Compose, Expo EAS                                       |

## 🚀 Getting Started

Installation instructions are omitted in this README.

The project is organized as a multi-app platform with mobile clients, a web simulation interface, and a backend service. If you are integrating it into your own environment, align the frontend, backend, and database configuration with your local runtime and deployment setup.

## 🏗 Architecture

TAXIORA uses a client-server architecture with real-time messaging at the center of the workflow.

Passenger and driver applications exchange live updates with the backend, while the simulation interface provides operational visibility for administrative and analytical scenarios. The server coordinates booking state, manages persistence, and broadcasts updates through Socket.IO so the ride lifecycle remains synchronized across all connected clients. Supporting services handle routing, driver selection, and scenario orchestration at a high level without exposing implementation-specific details.

## 🔒 Privacy & Security

The platform applies standard transport, authentication, and access-control practices appropriate for a real-time mobility system.

Sensitive session data is handled carefully, authenticated actions are protected, and operational data should be stored and transmitted through secured channels in any deployed environment.

## 🎯 Future Improvements

- Expand scenario coverage for more complex dispatch conditions.
- Add richer operational analytics and reporting views.
- Improve simulation controls for repeatable research workflows.
- Extend ride monitoring with more detailed journey states.
- Broaden support for advanced routing and assignment strategies.

## 👨‍💻 Author

**TAXIORA Project Team**

Built to showcase a modern, real-time taxi booking experience with a focus on clarity, operational realism, and simulation value.

## 📄 License

All rights reserved.
