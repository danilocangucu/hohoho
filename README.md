# Ho! Ho! Ho!

A festive website built as an open call for Christmas 2024. The winner received a free custom website created by me, Danilo Canguçu.

## About

This project features:

- Animated snowfall using **GSAP**
- Smooth page transitions and loading animations
- Playful, festive design

Built with **Next.js**, **React**, **Redux**, **React Hook Form**, **Chart.js**, **react-i18next**, **PostgreSQL**, and **AWS**.

The project is archived but still interactive.

## Local Setup

To run the project locally:

```bash
git clone <repo-url>
cd hohoho
npm install --legacy-peer-deps
npm run dev
````

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Deployment

The project is deployed automatically to an EC2 instance via **GitHub Actions** on every push to `main`.

* **Build and archive** the React app
* **Copy** the build to EC2
* **Extract**, backup old version, move new build
* **Reload Nginx** to serve the updated site

Secrets required for deployment:

* `EC2_HOST`
* `EC2_USER`
* `EC2_SSH_KEY`

## Status

Ended in December 2024. All rights reserved © 2024 Danilo Canguçu.