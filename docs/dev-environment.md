# Development environment

How to start the project. This is the page the agent must find when asked
"how do I start the project?".

Write commands exactly as they are typed. If a command differs on Windows,
give both versions.

## Requirements

- Docker and Docker Compose (recommended), or Node.js 24+ and Yarn 4 (`corepack enable`).
- Git.

## Start

### Using Docker (preferred)

```sh
docker compose up
```

### Using local environment

```sh
yarn install
yarn dev
```

The application opens at http://localhost:5173.

## Stop

### Using Docker

```sh
docker compose down
```

### Using local environment

Press `Ctrl+C` in the running terminal.

## Common problems

- Port 5173 is already in use: stop conflicting processes or adjust port mapping in compose.yaml.
