# React Native Project

This is a basic React Native project setup with TypeScript support.

## Getting Started

### Prerequisites

- Node.js (>= 16)
- React Native CLI
- Android Studio (for Android development)
- Xcode (for iOS development, macOS only)

### Installation

1. Install dependencies:
```bash
npm install
# or
yarn install
```

2. For iOS (macOS only):
```bash
cd ios && pod install && cd ..
```

### Running the App

#### Android
```bash
npm run android
# or
yarn android
```

#### iOS (macOS only)
```bash
npm run ios
# or
yarn ios
```

### Development

- Start the Metro bundler:
```bash
npm start
# or
yarn start
```

- Run tests:
```bash
npm test
# or
yarn test
```

- Lint code:
```bash
npm run lint
# or
yarn lint
```

## Project Structure

```
├── App.tsx                 # Main app component
├── index.js               # Entry point
├── package.json           # Dependencies and scripts
├── tsconfig.json          # TypeScript configuration
├── babel.config.js        # Babel configuration
├── metro.config.js        # Metro bundler configuration
├── android/               # Android-specific code
├── ios/                   # iOS-specific code
└── .gitignore            # Git ignore rules
```

## Features

- TypeScript support
- Dark/Light mode support
- Cross-platform (iOS & Android)
- Metro bundler configuration
- ESLint and Prettier setup