# Allergy-Safe Recipes App

A React Native mobile app built with Expo for personalized recipe suggestions, filtering out specific allergens (e.g., onions, chicken, shellfish, gluten, lactose). Integrates with the Spoonacular API for dynamic recipe data. Designed to help users with unique dietary needs find safe, delicious meals.

## Running the project
To run your project, run one of the following npm commands.

- npm run android
- npm run ios # you need to use macOS to build the iOS project - use the Expo app if you need to do iOS development without a Mac
- npm run web

## Features
- User profile with customizable allergy exclusions.
- Recipe search and suggestions via Spoonacular API.
- Local recipe book for saving favorites.
- Offline support for cached recipes.

## Tech Stack
- **Frontend**: React Native with Expo (JavaScript/ES6+).
- **API**: Spoonacular (Edamam as fallback).
- **Storage**: AsyncStorage for local data persistence.
- **Tools**: Expo CLI, Git, VS Code.

## Getting Started
1. Clone the repo: `git clone https://github.com/yourusername/allergy-safe-recipes-app.git`
2. Install dependencies: `cd allergy-safe-recipes-app && npm install`
3. Start the app: `npx expo start`

## Roadmap
- [x] Project setup and GitHub initialization.
- [ ] UI/UX wireframes and design.
- [ ] Core functionality (API integration, allergy filters).
- [ ] Testing and deployment.

## Contributing
Contributions welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License
MIT