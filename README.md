# SMART_ENERGY_SYSTEM

# Smart Device Management System

An implementation of a Python Object-Oriented Programming (OOP) framework modeled to track, monitor, and configure variable states of modular Smart Ecosystem products. Developed as a formal assignment submission for course component **EL 162 / 234 Object Oriented Programming** under Dr. Matthew Cobbinah.

## Core Features Implemented

*   **Encapsulation**: Private baseline states (`__device_id`, `__power_status`) initialized securely, preventing downstream direct alterations and forcing property validations.
*   **Inheritance**: Specific structural variants (`TemperatureSensor`, `SmartLight`, `SecurityCamera`) inherit safely from the base class `SmartDevice` utilizing `super()` injection hooks.
*   **Validation Rules**: System verifies input limits strictly (e.g., confirming explicit alpha-numeric bounds on setup keys, tracking brightness limits strictly inside `[0, 100]`).
*   **Menu-Driven Framework**: Implements an interactive console interface supporting continuous variable evaluation loops.

## How to Run the Program

Ensure you have a modern deployment runtime environment configured (`Python 3.8+` is recommended). 

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/smart-device-management-system.git](https://github.com/YOUR_GITHUB_USERNAME/smart-device-management-system.git)
   cd smart-device-management-system
