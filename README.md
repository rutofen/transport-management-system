# Transport Management System

A delivery management system built during my Full Stack practicum at Hi-Tel.
It has a REST API for transports and tracking, and a mobile app for drivers.

## What's inside

**Backend** (`/Backend`)
- REST API with Node.js and Express
- PostgreSQL database, with tables created on startup from a JSON definition
- Endpoints for transports (create, read, update, delete) and tracking records
- Jest tests for the transport and tracking routes
- Docker and docker-compose setup

**Mobile app** (`/Frontend`)
- React Native with Expo and TypeScript
- Screens for tracking a delivery and collecting a signature on delivery
- Forms for delivery status, users and pump details, with reusable table components

**CI**
- GitHub Actions workflow that runs ESLint on every push

## Tech

Node.js · Express · PostgreSQL · React Native · Expo · TypeScript · Jest · Docker · GitHub Actions

## Run the backend with Docker

```bash
git clone https://github.com/rutofen/transport-management-system.git
cd transport-management-system/Backend
cp .env.example .env
docker-compose up
```

## Run the mobile app

```bash
cd transport-management-system/Frontend
npm install
npx expo start
```
