# React Native Learning Notes

A personal collection of notes, guides, tips, and code snippets from my journey learning React Native.

---

## Table of Contents

- [Getting Started](#getting-started)
- [Project Setup](#project-setup)
- [Core Concepts](#core-concepts)
- [Useful Commands](#useful-commands)
- [Components](#components)
- [Navigation](#navigation)
- [APIs & State Management](#apis--state-management)
- [Styling](#styling)
- [Debugging & Troubleshooting](#debugging--troubleshooting)
- [Resources](#resources)
- [Tips](#tips)

---

## Getting Started

- React Native lets you build mobile apps using JavaScript and React.
- Install Node.js, npm, and either Android Studio or Xcode for simulators/emulators.

## Project Setup

```bash
npx react-native init MyApp
cd MyApp
npx react-native run-android   # or run-ios
```

## Core Concepts

- **JSX** for UI components
- **Props**: Pass data to components
- **State**: Manage local component data
- **Hooks**: Use state and lifecycle features in functional components

## Useful Commands

```bash
npx react-native start        # Start Metro bundler
npx react-native run-android # Run app on Android
npx react-native run-ios     # Run app on iOS
```

## Components

- **View**: Container for UI elements
- **Text**: Display text
- **Image**: Show images
- **Button**: Basic button

## Navigation

- [React Navigation](https://reactnavigation.org/) is the standard library
- Install: `npm install @react-navigation/native`
- Stack, Tab, Drawer navigation patterns

## APIs & State Management

- Use `fetch` or libraries like `axios` for API calls
- State: useState, useReducer, or global state with Redux/MobX

## Styling

- Styles are JS objects: `{ color: 'red', fontSize: 14 }`
- Use StyleSheet for better performance

## Debugging & Troubleshooting

- Use Chrome DevTools, React Native Debugger
- Common errors: Metro bundler issues, emulator setup

## Resources

- [React Native Docs](https://reactnative.dev/)
- [Expo Docs](https://docs.expo.dev/)
- [Awesome React Native GitHub](https://github.com/jondot/awesome-react-native)

## Tips

- Always test on both iOS and Android
- When stuck, search error messages or check Stack Overflow
- Try building small sample apps to practice

---

*Add more notes, code samples, and questions as you learn!*