# IN5320 Group Project

This project was bootstrapped with the DHIS2 Application Platform.

## Table of contents
- [Prerequisites](#prerequisites)
- [Quick start](#quick-start)
- [Scripts](#scripts)
- [Useful links](#useful-links)
- [Troubleshooting](#troubleshooting)

## Prerequisites
- Node.js (LTS)
- Yarn or npm
- Access to a running DHIS2 backend for local development

## Quick start

1. Start the DHIS2 backend (example):
    ```
    npx dhis-portal --target=https://research.im.dhis2.org/in5320g02
    ```

2. Install dependencies:
    ```
    yarn install
    ```

3. Start the development server:
    ```
    yarn start
    ```
    Open http://localhost:3000 — the app reloads on edits and lint errors appear in the console.

Credentials for the example backend:
```
Username: in5320
Password: P1@tform
```

## Scripts

- `yarn start` — Run the app in development mode.
- `yarn test` — Run tests located in `/src`. See: https://platform.dhis2.nu/#/scripts/test
- `yarn build` — Build a production bundle in the `build` folder. A deployable `.zip` is available at `build/bundle`. See: https://platform.dhis2.nu/#/scripts/build
- `yarn deploy` — Deploy the built app to a DHIS2 instance (prompts for server URL and credentials). Run `yarn build` before `yarn deploy`. See: https://platform.dhis2.nu/#/scripts/deploy

## Useful links
- DHIS2 Application Platform docs: https://platform.dhis2.nu/
- DHIS2 Application Runtime docs: https://runtime.dhis2.nu/
- React docs: https://reactjs.org/

## Troubleshooting
- If the app doesn't load, confirm the DHIS2 backend URL is reachable and credentials are correct.
- If dependency installation fails, try removing `node_modules` and reinstalling (`yarn install`).

Feel free to expand this README with project-specific details (features, architecture, contributing guidelines).
