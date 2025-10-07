# Clock and Prayer Times Application

This project is a simple web application that displays the current time and Muslim prayer times based on the user's location. It is built using TypeScript and follows a modular structure for easy maintenance and scalability.

## Features

- Displays the current time in a user-friendly format.
- Calculates and displays Muslim prayer times based on the user's location.
- Responsive design to ensure usability across different devices.

## Project Structure

```
clock-app
├── src
│   ├── components
│   │   ├── Clock.ts          # Displays the current time
│   │   ├── PrayerTimes.ts    # Calculates and displays prayer times
│   │   └── index.ts          # Exports components for easy import
│   ├── services
│   │   └── prayerTimesService.ts # Fetches prayer times from an API
│   ├── utils
│   │   └── timeUtils.ts      # Utility functions for time formatting and calculations
│   └── index.ts              # Entry point of the application
├── public
│   └── index.html            # Main HTML file
├── package.json              # npm configuration file
├── tsconfig.json             # TypeScript configuration file
└── README.md                 # Project documentation
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd clock-app
   ```
3. Install the dependencies:
   ```
   npm install
   ```

## Usage

To start the application, run:
```
npm start
```

Open your browser and navigate to `http://localhost:3000` to view the application.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.