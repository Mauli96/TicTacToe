# TicTacToe - Classic Game App

A modern take on the classic TicTacToe game for Android, designed for an engaging and seamless gaming experience. The app features an intuitive UI and real-time multiplayer functionality, achieving sub-second latency for smooth gameplay.

## Features

- **Classic Gameplay**: Play the timeless game of TicTacToe against another player in real-time.
- **Intuitive UI**: Designed with Jetpack Compose, using Canvas and Material Design for a visually appealing and responsive interface.
- **Real-Time Multiplayer**: Enabled through WebSockets for instant interaction and updates between players.
- **Backend Integration**: Built with Ktor framework to support real-time communication and manage game sessions efficiently.
- **Dependency Injection**: Powered by Dagger Hilt to ensure scalable and maintainable code architecture.
- **API Communication**: Utilized Retrofit and RESTful APIs for seamless backend communication.

## Tech Stack

### Frontend:
- **Jetpack Compose**: Designed responsive UI components.
- **Material Design**: Ensured a clean and modern look.
- **Canvas**: Used for custom game board rendering.

### Backend:
- **Ktor Framework**: Built a lightweight and efficient backend.
- **WebSockets**: Integrated for real-time data exchange between players.
- **RESTful APIs**: Supported non-real-time backend communication.

### Additional Tools:
- **Dagger Hilt**: Simplified dependency injection for better scalability.
- **Retrofit**: Simplified HTTP communication with the backend.

## Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Open the project in Android Studio.
3. Build and run the application on an emulator or a physical device.

## How to Play

1. Launch the app and choose to host or join a game.
2. Play against another player in real-time by making your moves on the board.
3. The game updates instantly to reflect both players' moves.
4. Enjoy the seamless and lag-free experience!
