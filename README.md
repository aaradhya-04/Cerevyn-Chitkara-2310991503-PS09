# Mind Match — Adaptive Memory Matching Game

**Cerevyn Solutions | Round One Technical Assessment**

## Candidate Details

- **Name:** Aaradhya Mittal
- **Roll Number:** 2310991503
- **Branch:** BE CSE
- **University:** Chitkara University, Rajpura, Punjab
- **Problem Statement:** PS09 — Adaptive Memory Matching Game

## 1. Project Overview

Mind Match is a browser-based memory matching game in which players reveal cards and find matching pairs. The game tracks player performance and adjusts the difficulty of the next round based on a predefined rule.

The project focuses on fundamental software development concepts, including game-state management, event handling, performance tracking, automated testing, and continuous integration.

## 2. Objectives

- Develop an interactive browser-based memory game.
- Implement matching logic for eight pairs in a 4 × 4 grid.
- Track moves, completed pairs, and elapsed time.
- Provide at least two difficulty levels.
- Adjust the next round's difficulty based on previous performance.
- Handle rapid clicks, repeated selections, and game restarts correctly.
- Include automated tests and a documented deployment plan.

## 3. Technologies Used

- **HTML5:** Game structure.
- **CSS3:** Styling and responsive layout.
- **JavaScript:** Game logic and interaction handling.
- **Node.js:** Test execution and development scripts.
- **Git and GitHub:** Version control and source-code hosting.
- **GitHub Actions:** Continuous integration and automated testing.
- **Microsoft Azure:** Proposed hosting and deployment platform.

## 4. Key Features

- Interactive card grid with matching pairs.
- Move counter and completed-pair tracking.
- Elapsed-time tracking.
- Multiple difficulty levels.
- Performance-based difficulty adjustment.
- Safe handling of mismatched cards and repeated clicks.
- Restart functionality.
- Anonymous session-result storage.
- Automated tests and continuous integration.

## 5. How the Game Works

1. The player starts a new round.
2. Cards are shuffled and displayed face down.
3. The player selects two cards.
4. Matching cards remain revealed; mismatched cards are hidden after a short delay.
5. The game updates the move count and completed pairs.
6. Once all pairs are matched, the game displays the round result.
7. The next round's difficulty is selected using the documented performance rule.

## 6. Installation and Setup

### Prerequisites

- Node.js installed on your system.
- A modern web browser.
- Git (optional, for cloning the repository).

### Steps

Clone the repository:

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_PROJECT_FOLDER>
```

Install dependencies, if required:

```bash
npm install
```

Run automated tests:

```bash
npm test
```

Start the application:

```bash
npm start
```

Open the local URL specified by the project configuration in your browser.

> Note: The commands above must match the actual scripts defined in `package.json`. If the project uses a different local server or test command, update these instructions accordingly.

## 7. Testing

The project should be tested against the following scenarios:

- Successful card matching.
- Mismatched card handling.
- Prevention of a third selection while a mismatch is being resolved.
- Repeated clicks on selected or matched cards.
- Restarting during a pending delay.
- Difficulty adjustment based on previous performance.
- Successful completion of a round.

Automated test results should be verified before submission.

## 8. Continuous Integration

GitHub Actions can automatically install dependencies and run the test suite whenever changes are pushed to the repository or a pull request is opened.

The workflow configuration is intended to be maintained under:

`.github/workflows/ci.yml`

## 9. Azure Deployment Plan

The game can be hosted using **Azure Static Web Apps** if it is delivered as a static browser application. Azure App Service is an alternative if the final implementation requires a running server.

The deployment documentation should cover the chosen hosting service, configuration, deployment steps, monitoring, and cost assumptions.

Live Azure deployment is optional under the assessment requirements.

## 10. Limitations

- The difficulty adjustment uses predefined rules rather than a trained AI model.
- Browser-based storage may be cleared by the user.
- The application is an educational game and does not provide a clinical or cognitive assessment.
- Cloud deployment is not considered complete unless it has actually been performed and verified.

## 11. Future Enhancements

- Add more card themes and visual designs.
- Introduce additional difficulty levels.
- Provide a leaderboard using anonymous player identifiers.
- Improve accessibility and keyboard navigation.
- Add more automated tests and browser-based testing.

## 12. Author

**Aaradhya Mittal**
BE CSE | Chitkara University, Rajpura, Punjab
Roll Number: 2310991503

**Project:** Mind Match — PS09 Adaptive Memory Matching Game
**Assessment:** Cerevyn Solutions — Round One Technical Assessment
