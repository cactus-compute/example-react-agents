# Cactus Agent Example App

A React Native demo app showcasing the CactusAgent class for AI-powered productivity features.

## Quickstart

Click GIF below to watch a short video quickstart:

[![Cactus Agents for React Native 🌵](https://github.com/user-attachments/assets/4d809fc1-6e95-484b-ad79-afad88d5ffe4)](https://www.tella.tv/video/cactus-agents-for-react-native-021x)

## Overview

This app demonstrates how to integrate local AI agents into a React Native application using the Cactus framework. The app features a text input where AI inference is automatically triggered each time you type a period (`.`), allowing for real-time AI assistance and suggestions.

## How It Works

1. Type text into the app's text input field
2. Each time you enter a period (`.`), the CactusAgent triggers inference
3. The AI processes your input and provides relevant suggestions or responses
4. Continue typing to see real-time AI assistance

## Agent Tools

The CactusAgent has access to three productivity tools:

- **Set Reminder**: Creates reminders for specific dates and times based on your input
- **Write Draft Email**: Generates draft emails with suggested subjects when appropriate
- **Add To-Do**: Creates to-do items from tasks mentioned in your text

Each tool suggestion appears as a recommended action that you can accept or dismiss.

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npx expo run
   ```

3. Run on your preferred platform:
   - iOS Simulator
   - Android Emulator  
   - Physical device with Expo Go

This is an Expo project with file-based routing.
