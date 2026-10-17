# MD Corp Ranks

A company review platform where employees share anonymous and verified feedback about their employers, built in two iterations (MVP 1 and MVP 2) as a multidisciplinary project.

| | |
|---|---|
| Course | Multidisciplinary Project |
| University | Politecnico di Milano, M.Sc. Computer Science and Engineering |
| Semester | Spring 2024 |
| Type | Team project |

## Overview

- **Frontend:** React and TypeScript, built with Vite.
- **Backend:** Spring Boot 3 on Java 17, with a PostgreSQL database started through Docker Compose.
- **Iterations:** [`MVP_1/`](MVP_1/) is the first version of the platform and [`MVP_2/`](MVP_2/) the second, each with its own frontend and backend.

## Repository structure

| Path | Contents |
|---|---|
| [`MVP_1/frontend/`](MVP_1/frontend/) | First version of the web app (React, TypeScript, Vite) |
| [`MVP_1/backend/`](MVP_1/backend/) | First version of the API (Spring Boot) |
| [`MVP_2/frontend/`](MVP_2/frontend/) | Second version of the web app |
| [`MVP_2/Backend/`](MVP_2/Backend/) | Second version of the API |

## Getting started

Start the database and the backend (example for MVP 2):

```sh
cd MVP_2/Backend
docker compose up -d
./mvnw spring-boot:run
```

Start the frontend in a second terminal:

```sh
cd MVP_2/frontend
npm install
npm run dev
```

## Tech stack

React, TypeScript, Vite, Spring Boot, Java 17, PostgreSQL, Docker Compose.

## Team

Rishabh Tiwari, Simon Fladen Lie and Alice Norrthon.
