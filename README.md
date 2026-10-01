# Dataset Metadata Collector
A simple, browser-based app to collect dataset metadata and export output as a JSON file.

Live app: https://mrcieu.github.io/dataset-metadata-collector/


## What is this?
Dataset metadata collector is a single-page app that walks you through a form of different sections to help collect dataset details (e.g. dataset summary, documentations, etc.). After completing form, you can download the result as a .json file which can be accessed for local use.

## Privacy: your data stays on your device
- The app runs **entirely in your web browser**.
- **Nothing you enter on the form is sent to a server, database, or cloud services.** There is no backend to it.
- The only output is the JSON file **you choose to download**. What you do with this file as an end user is up to you.

  > You can verify this yourself: open your broswer's developer tools (F12)
  > Go to the Network tab, fill in the form, and confirm that no requests are mad to any domain other than the one serving the app.

## How to use it?
1. Open the app at https://mrcieu.github.io/dataset-metadata-collector/
2. **Read through the instructions** and click on the [Create Dataset](https://mrcieu.github.io/dataset-metadata-collector/summary) button on the bottom of the page
3. **Fill the fields on different sections of the form** at your own pace
4. **Review all your entries**
5. **Download results as JSON** file using the **Export JSON** button
6. **Keep your json file**, store this file for your usage at your convenience.
7. Click **Reset** button to reset form


## Running it locally
You might need to run or modify the app yourself, this is where **React Router** comes in.

## Welcome to React Router!

A modern, production-ready template for building full-stack React applications using React Router.

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/remix-run/react-router-templates/tree/main/default)

### Features

- 🚀 Server-side rendering
- ⚡️ Hot Module Replacement (HMR)
- 📦 Asset bundling and optimization
- 🔄 Data loading and mutations
- 🔒 TypeScript by default
- 🎉 TailwindCSS for styling
- 📖 [React Router docs](https://reactrouter.com/)

## Getting Started

### Installation

Install the dependencies:

```bash
npm install
```

### Development

Start the development server with HMR:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## Building for Production

Create a production build:

```bash
npm run build
```

## Deployment

### Docker Deployment

To build and run using Docker:

```bash
docker build -t my-app .

# Run the container
docker run -p 3000:3000 my-app
```

The containerized application can be deployed to any platform that supports Docker, including:

- AWS ECS
- Google Cloud Run
- Azure Container Apps
- Digital Ocean App Platform
- Fly.io
- Railway

### DIY Deployment

If you're familiar with deploying Node applications, the built-in app server is production-ready.

Make sure to deploy the output of `npm run build`

```
├── package.json
├── package-lock.json (or pnpm-lock.yaml, or bun.lockb)
├── build/
│   ├── client/    # Static assets
│   └── server/    # Server-side code
```

## Styling

This template comes with [Tailwind CSS](https://tailwindcss.com/) already configured for a simple default starting experience. You can use whatever CSS framework you prefer.

---

Built with ❤️ using React Router.
