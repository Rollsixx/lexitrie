# LexiTrie

A Trie-based dictionary app built with Expo and React Native.

## Features

- **Smart Autocomplete** - Instant word suggestions using Trie data structure
- **Fuzzy Search** - Levenshtein distance algorithm for typo-tolerant searching
- **Favorites** - Save your favorite words
- **Search History** - Track your recent searches
- **Dark/Light Theme** - Automatic theme based on system settings

## Tech Stack

- **Framework**: Expo SDK 52
- **Language**: TypeScript
- **State Management**: Zustand
- **Data Structures**: Trie, Levenshtein Distance

## Project Structure

```
src/
├── algorithms/       # Trie & Levenshtein implementations
├── components/       # Reusable UI components
├── data/            # Dictionary data loading
├── hooks/           # Custom React hooks
├── store/           # Zustand state stores
├── theme/           # Theme configuration
└── types/           # TypeScript types
```

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm start

# Run on Android
npm run android
```

## Build

```bash
# Build Android APK
npx expo run:android
```

The APK will be generated at `android/app/build/outputs/apk/debug/`

## Dictionary

- Contains 10,000+ English words
- Word definitions loaded from dictionary-filtered.json