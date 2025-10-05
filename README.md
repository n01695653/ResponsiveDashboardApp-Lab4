# Responsive Dashboard App - CPAN213 Lab 4

## Student Information
- **Name:** MaksudHusen A Malek
- **Student ID:** N01695653
- **Course:** CPAN 213 - Cross-Platform Mobile Application Development
- **Lab:** Lab 4 - Creating Responsive Layouts with Flexbox
- **Date:** 5\10\2025

## Project Overview
This React Native application demonstrates advanced responsive design techniques using Flexbox. The app features a fully responsive dashboard that adapts to different screen sizes, orientations, and platforms.

## Features Implemented
-  **Responsive Grid System** - Adapts columns based on screen size
-  **Dashboard Widgets** - Statistics cards with trend indicators
-  **Platform-Specific Styling** - iOS and Android optimizations
-  **Orientation Handling** - Automatic layout adjustments
-  **Theme System** - Consistent colors, typography, and spacing
-  **Performance Optimized** - 60fps smooth animations

## Technologies Used
- React Native 0.72+
- React Native Vector Icons
- Flexbox Layout System
- Dimensions API for responsive design

## Installation & Setup

### Prerequisites
- Node.js 16+
- Android Studio with emulator
- React Native CLI

### Quick Start
```bash
# Clone repository
git clone [your-repository-url]
cd ResponsiveDashboardApp

# Install dependencies
npm install

# Start Metro bundler
npx react-native start

# In new terminal - Run on Android
npx react-native run-android

Responsive Design Features
Breakpoint System
Small Phones (< 350px): 1 column layout

Medium Phones (350-400px): 2 column layout

Large Phones (400-500px): 2 column layout

Tablets (500-768px): 3 column layout

Large Tablets (> 768px): 4 column layout

Responsive Utilities
wp() - Width percentage calculator

hp() - Height percentage calculator

rf() - Responsive font scaling

getGridColumns() - Dynamic column calculation

Platform Adaptations
iOS: Native shadow properties, specific typography

Android: Elevation shadows, Material Design colors

Both: Consistent spacing, adaptive padding

Key Components
DashboardHeader
Responsive app bar with navigation

Platform-specific status bar handling

Adaptive typography and spacing

ResponsiveGrid
Dynamic column calculation

Orientation change support

Performance-optimized rendering

Widget System
BaseWidget for consistent structure

StatisticWidget for data display

Reusable and customizable

Performance Optimizations
StyleSheet.create() for all styles

Memoized responsive calculations

Optimized re-renders with React hooks

Efficient dimension change handling

Testing
The app has been tested on:

Android Phones (Multiple screen sizes)

 Android Tablets

 Different orientations


