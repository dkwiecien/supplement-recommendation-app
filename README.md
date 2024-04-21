# Supplement Recommendation App

## Project setup

Prerequisites:
- `node.js` LTS (20.11.1) and `npm` (https://nodejs.org/en/download/)
- `pnpm` (https://pnpm.io/installation)
- `docker` and `docker-compose` (https://docs.docker.com/get-docker/)
- If using VSCode, install [EditorConfig plugin](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig).

To setup the project:

1. Clone the repository,
3. In ./client directory run `pnpm install` to install tooling,
4. Run your Docker Desktop app,
5. In ./dockerfiles directory run  `docker-compose up` to create the database,
6. In ./client directory run `pnpm run dev`.
