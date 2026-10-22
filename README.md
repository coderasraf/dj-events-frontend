# DJ Events Frontend

The starting point for a DJ events web app built with Next.js. At this stage the repository contains only the initial Next.js scaffold.

![Next.js](https://img.shields.io/badge/Next.js-12-000000?logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white)

## About

Created in 2022 as the first step of the DJ Events project from Brad Traversy's Next.js course, a learning project for building a full-stack events app with Next.js. Only the `create-next-app` setup has been committed so far; the events pages, backend integration and authentication from the course have not been built in this repo.

## Current State

- Next.js 12 project created with `create-next-app`
- Default home page (`pages/index.js`) and example API route (`pages/api/hello.js`)
- ESLint configured with `eslint-config-next`
- CSS Modules for styling

## Tech Stack

- Next.js 12
- React 18
- CSS Modules
- ESLint

## Getting Started

Prerequisites: Node.js and npm.

```bash
git clone https://github.com/coderasraf/dj-events-frontend.git
cd dj-events-frontend
npm install
npm run dev      # http://localhost:3000
```

Other scripts:

```bash
npm run build    # production build
npm start        # serve the production build
npm run lint     # run ESLint
```

## Project Structure

```text
├── pages/
│   ├── _app.js
│   ├── index.js
│   └── api/hello.js
├── public/
├── styles/          # globals.css, Home.module.css
└── next.config.js
```

## Author

Built by **Ashraf Siddik**, Shopify developer & CRO specialist.
- Website: [ashraf-siddik.com](https://ashraf-siddik.com)
- GitHub: [@coderasraf](https://github.com/coderasraf)
