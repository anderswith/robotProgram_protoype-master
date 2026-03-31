# RobertsRobotBar Prototype

This project is an early prototype of a system for controlling a Universal Robots robotic arm to mix drinks.

The purpose of the prototype was to establish a simple solution for communicating with the robot and executing drink scripts.
The project was used in practice during Tønder Festival.

---

## Functionality

* Communication with the robot via TCP
* Execution of scripts for drink mixing
* Simple user interface for selecting drinks
* REST API acting as a link between frontend and robot

---

## Technology

* Python
* Flask (REST API)
* HTML frontend
* SQLite database
* TCP communication with the robot

---

## Architecture

### Frontend

* Implemented in HTML
* Communicates with the backend via HTTP requests

### Backend

* Built as a REST API using Flask
* Receives requests from the frontend
* Sends commands to the robot via TCP
* Handles simple logic for sequential execution of scripts

### Database

* SQLite used for storing recipes and configuration
