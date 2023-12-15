# Jotion - Fullstack Notion Clone

![Jotion Logo](./public/logo.svg)

Welcome to Jotion, a Notion clone built with Next.js 13, React, Convex, and Tailwind. This project aims to replicate the core features of Notion while providing a powerful and flexible framework for building collaborative note-taking and documentation platforms.

## Live Site

Explore Jotion on our [live site](https://jotion-note-taking-app-facelift2376.vercel.app/) (replace '#' with your actual live site URL).

## Key Features

- **Real-time Database:** Keep your data synchronized across users in real-time.
- **Notion-style Editor:** A powerful editor inspired by Notion's user interface.
- **Light and Dark Mode:** Toggle between light and dark modes for a comfortable reading experience.
- **Infinite Children Documents:** Organize your content hierarchically with infinite children documents.
- **Trash Can & Soft Delete:** Safely delete documents with the ability to recover them from the trash can.
- **Authentication:** Secure your application with user authentication.
- **File Management:** Upload, delete, and replace files within your documents.
- **Live Icons:** Enjoy real-time updates to icons for each document.
- **Expandable Sidebar:** Easily navigate through your documents with an expandable sidebar.
- **Full Mobile Responsiveness:** Access Jotion seamlessly on various devices.
- **Web Publishing:** Share your notes with the world by publishing them to the web.
- **Collapsible Sidebar:** Maximize your workspace with a fully collapsible sidebar.
- **Landing Page:** Welcome users with an engaging landing page.
- **Cover Image:** Customize each document with a cover image.
- **Recover Deleted Files:** Restore accidentally deleted files.

### Prerequisites

**Node version 18.x.x**

### Cloning the repository

```shell
git clone https://github.com/AntonioErdeljac/notion-clone-tutorial.git
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

### Setup Convex

```shell
npx convex dev

```

### Start the app

```shell
npm run dev
```

# Acknowledgments

Special thanks to [Antonio Erdeljac](https://www.youtube.com/c/CodeWithAntonio) for providing an insightful and comprehensive tutorial on building a Notion clone. This project would not have been possible without his guidance and expertise.

Check out the [full tutorial on YouTube](https://www.youtube.com/watch?v=ZbX4Ok9YX94) by [Code With Antonio](https://www.youtube.com/c/CodeWithAntonio).

Thank you, Antonio, for sharing your knowledge and inspiring this project!

Follow Antonio Erdeljac on [GitHub](https://github.com/AntonioErdeljac).
