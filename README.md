# Feeding Potato 🥔

A React Native application with a beautiful welcome page.

## Features

- Beautiful gradient UI with modern design
- Welcome page with feature highlights
- Cross-platform support (iOS & Android)
- Ready to extend with navigation and more screens

## Getting Started

### Prerequisites

- Node.js >= 18
- React Native development environment set up
- For iOS: Xcode and CocoaPods
- For Android: Android Studio and SDK

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. For iOS, install pods:
   ```bash
   cd ios && pod install && cd ..
   ```

### Running the App

**Android:**
```bash
npm run android
```

**iOS:**
```bash
npm run ios
```

**Start Metro Bundler:**
```bash
npm start
```

## Project Structure

```
feeding-potato/
├── App.js              # Main application component with Welcome page
├── index.js            # Entry point
├── app.json            # App configuration
├── package.json        # Dependencies and scripts
├── babel.config.js     # Babel configuration
└── metro.config.js     # Metro bundler configuration
```

## Welcome Page

The welcome page features:
- App logo and title
- Descriptive subtitle
- Feature highlights with icons
- Call-to-action button
- Modern gradient background

## Next Steps

- Add navigation (React Navigation)
- Create additional screens
- Implement state management
- Add API integration
- Customize styling and branding

## License

MIT
