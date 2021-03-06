# PenBoard

This is a minimalistic kanban board inspired by Trello and Linear, made 100% with TypeScript. The codebase is split up into 2 projects, frontend and backend.

[Video Submission](https://drive.google.com/file/d/13_Qw6K3spX0HxHlUd8QwjOTRczkGQAP6/view?usp=sharing)

## Backend

### Tech Stack

- NodeJS - JavaScript runtime
- Express - Lightweight and modural web framework
- MongoDB - Database persistence layer
- Mocha & Chai - Unit testing
- Heroku - Fully managed hosting service

### Architecture

The project follows a 3 layer architecture for clear separation of concerns.

- Models - Mongoose schemas and data models
- Services - Business Logic
- Routes - API public interface and endpoints

```
Routes --> Services --> Models
```

### Installation

Go to the root of the `backend` folder, install dependencies and start development build.

```
$ cd backend/ && npm i && npm run dev
```

## Frontend

### Tech Stack

- NextJS - React framework
- Material UI - Components library
- Redux - State management
- Vercel - Hosting Service with CDN

### Installation

Go to the root of the `frontend` folder, install dependencies and start development build.

```
$ cd frontend/ && npm i && npm run dev
```
