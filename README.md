# dapr

Tiny Node/Express service with a `/health` endpoint, packaged with Docker.

## Why this repo exists
I’m a Scrum Master/Agile Delivery Lead. I don’t code for my day job, but I work closely with engineers and need to understand delivery constraints, release hygiene, and what “good” looks like for reliability. This repo is a small proof project that shows how I learn and collaborate in technical environments.

## What it includes
- Node/Express service with a `/health` endpoint
- Docker support for repeatable local setup
- [Optional: Docker Compose for local run]
- [Optional: GitHub Actions CI for lint/tests/build]

## Run locally (Node)
```bash
npm install
npm start
curl http://localhost:3000/health
