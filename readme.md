# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### 1. Clone the repo

```bash
git clone https://github.com/ObelusFamily/Anythink-Market-5lblb.git
```

### 2. Install Docker

Please follow the instructions for your OS:

- [Windows](https://docs.docker.com/docker-for-windows/install/)
- [Mac](https://docs.docker.com/docker-for-mac/install/)
- [Linux](https://docs.docker.com/engine/install/)

Check if Docker and Docker Compose are installed:

```bash
docker -v
docker-compose -v
```

### 3. Start the app

```bash
docker-compose up
```

### 4. Open the app

- Test Frontend: http://localhost:3000/api/ping
- Test Backend: http://localhost:3001/register

### 5. Stop the app

```bash
docker-compose down
```
