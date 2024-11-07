# Gishushu Traffic Light Control System

## Project Overview
The Gishushu Traffic Light Control System is a simulation design to manage traffic flow at a busy four-way intersection in Gishushu. It aims to minimize traffic congestion and enhance safety by following a systematic light cycle. The design can be used for educational or simulation purposes to understand traffic flow management in urban settings.

## Specifications

### 1. Design Goals
- **Traffic Flow Management**: Ensure efficient movement of vehicles by regulating the duration of green, yellow, and red lights.
- **Safety**: Reduce collision risks by controlling each direction independently.
- **Reliability**: Implement a predictable cycle that helps drivers anticipate light changes.

### 2. Traffic Light States
The traffic light system alternates between four main states:
   - **State 1**: North-South Green, East-West Red – Allows traffic flow for North-South.
   - **State 2**: North-South Yellow, East-West Red – Signals North-South drivers to prepare to stop.
   - **State 3**: North-South Red, East-West Green – Allows traffic flow for East-West.
   - **State 4**: North-South Red, East-West Yellow – Signals East-West drivers to prepare to stop.

### 3. Cycle Logic
The traffic light changes are managed based on timers:
   - **Green Duration**: 30 seconds per direction.
   - **Yellow Duration**: 5 seconds per direction.
   - The cycle repeats continuously, alternating between North-South and East-West traffic flows.

## How to Use
To view the project:
1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/YourUsername/Traffic_lights_state_diagram.git
