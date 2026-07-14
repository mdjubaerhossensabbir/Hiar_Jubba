# Hiar Jubba

This repository contains a simple Vite + React application scaffold for deployment on Render, plus imported Image-Code-Gen source in `stylescan-app/`.

## Deployment

- Install dependencies: `npm install`
- Build: `npm run build`
- Preview: `npm run preview`

## Image-Code-Gen source

The `stylescan-app/` directory contains the imported source from the public Image-Code-Gen repository (`artifacts/stylescan-app`). It is included for later integration and review.

## Render

Use Render Web Service deployment with the following settings:
- Build Command: `npm install && npm run build`
- Start Command: `npm run preview --host 0.0.0.0 --port $PORT`
