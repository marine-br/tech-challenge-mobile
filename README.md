# Flutter Live Vehicle Tracker Challenge

Welcome to the Flutter Live Vehicle Tracker Challenge! This challenge aims to evaluate your skills in building a real-time vehicle tracking application using Flutter. Follow the guidelines below to showcase your expertise.

## Challenge Objectives

1. \*Map Visualization:
   - Plot vehicle markers on the map.
   - Utilize either `flutter_map`, `flutter_google_map` or any other package for map integration.
2. \*Real-time Updates:
   - Implement a polling mechanism to update vehicle locations every 30 seconds.
   - Manage state efficiently for real-time map updates without specific preference for state management packages.
3. \*Vehicle Details Screen:
   - Create a detailed screen for each vehicle.
   - Navigate to the details screen when a vehicle marker is clicked.

## Getting Started

1. \*Fork this repository.
2. \*Clone your forked repository:
   ```bash
   git clone https://github.com/marine-br/tech-challenge-mobile.git
   cd flutter-live-vehicle-tracker
   ```
   Follow instructions in the API section to access vehicle data.

## API Usage

To get user token:

```
API Endpoint: https://api-dev.dotelematics.com/api/auth/login
Method: POST
body: {
  "email": "teste_tecnico@dotelematics.com",
  "password": "2345678"
}
```

To obtain vehicle data:

```
API Endpoint: https://api-dev.dotelematics.com/tracking/realtime
Method: GET
Headers: Authorization: { user_token }
```

## Suggested Packages

Feel free to use the following packages from pub.dev:

- `flutter_modular`: Modularize your Flutter application.
- `flutter_map_marker_cluster`: Cluster markers for improved map performance.
- `flutter_map` or `flutter_google_map`: Integrate maps into your Flutter app.
- `map_launcher`: Launch external maps for navigation.

## Contribution Guidelines

1. Create a new branch:

```bash
git checkout -b feature/your-feature
```

2. Implement the required features and enhancements.
3. Commit your changes:

```bash
git commit -m “Implement live vehicle tracking feature”
```

4. Push to your branch:

```bash
git push origin feature/your-feature
```

5. Open a pull request on GitHub.

## Evaluation Criteria

- Adherence to the specified objectives.
- Code quality, readability, and maintainability.
- Efficient state management for real-time updates.
- User interface design and responsiveness.
  Feel free to explore additional packages or technologies to enhance your solution. We look forward to seeing your creative and well-crafted submissions! Happy coding!**\***
