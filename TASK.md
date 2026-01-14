# iOS Take-Home Task – Weather App

## Overview
Build a simple Weather App that demonstrates your understanding of:
- Async programming
- Memory management
- UI development
- Architecture patterns in iOS

The goal is to demonstrate concepts, not to build a production-ready app.

---

## UI Design
Follow the provided Figma design:
https://www.figma.com/design/LG1aes1XuKvyeo6ZWOhQkh/Apple-Weather-App-Clone--Community---Copy

### Screens
- Main weather screen with current conditions
- Forecast list view

### UI Constraints
- UI must be implemented **programmatically**
- Use **Auto Layout**
- Must use **LBTATools** for layout
- Handle error and progress state

---

## API Integration

Use any public weather API (e.g. OpenWeatherMap).

### Sequential API Calls
Implement **3 sequential API calls**:
1. Fetch current weather
2. Fetch hourly forecast
3. Fetch 5-day forecast

### Concurrent API Calls
Implement a separate feature that:
- Makes **3 concurrent API calls** (e.g. weather for 3 cities)
- Displays a message when all requests complete

### Important
- Demonstrate proper background thread handling
- Use **async/await**

---

## Architecture Requirements

You **must** use:
- MVVM architecture
- Coordinator pattern for navigation
- Combine for View ↔ ViewModel communication

### Separation of Concerns
- Network layer
- View layer
- Coordinator layer

Add inline comments or README notes explaining your decisions.

---

## Libraries
- Must use **LBTATools**
- Other third-party libraries are allowed
- Clearly document why you chose them

---

## Notes
- Focus on clarity and correctness
- Add inline comments where appropriate
- Clean, readable code is preferred over extra features

