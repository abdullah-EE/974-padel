# 974 Padel

A cross-platform product prototype for the padel community in Qatar, built with **React Native, Expo, and TypeScript**.

The project explores a mobile-first experience for discovering courts, finding players, following competitions, and bringing several padel-community workflows into one app.

## Product flows

The current frontend includes flows for:

- court discovery
- play and match discovery
- player challenges
- tournaments
- leaderboard views
- player profiles
- submissions and community activity

The interface is built as a real multi-screen mobile application rather than a static mockup, with shared state, reusable components, routing, animations, and responsive web support.

## Tech stack

- **React Native**
- **Expo 54**
- **Expo Router**
- **TypeScript**
- React Navigation
- React Native Reanimated
- Moti
- Async Storage
- Expo Location

## Project structure

~~~text
app/          screens and Expo Router navigation
src/components/
src/data/     prototype datasets
src/hooks/
src/state/    shared application state
src/theme/
src/types/
src/utils/
~~~

## Run locally

~~~bash
npm install
npm run start
~~~

Other targets:

~~~bash
npm run android
npm run ios
npm run web
npm run typecheck
~~~

## Status

This is a **frontend MVP**. Product flows currently use mock/local data and are intended to validate the application experience before connecting a production backend, payments, or live venue systems.

## What this project demonstrates

- cross-platform mobile product development
- application state and navigation architecture
- building a consistent design system across many screens
- translating a real local-market idea into a functional prototype
