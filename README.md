# Discord Clone 2

A Discord clone built with Next.js, TailwindCSS, Stream, and Clerk. This project aims to replicate the core functionalities of Discord using modern web technologies.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [Environment Variables](#environment-variables)
- [Additional Information](#additional-information)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed on your machine
- An account on [Stream](https://getstream.io)
- An account on [Clerk](https://clerk.dev)

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/yourusername/discord-clone-2.git
   ```

2. Navigate to the project directory:

   ```
   cd discord-clone-2
   ```

3. Install the dependencies:

   ```
   npm install
   ```

## Running the Project

To run the project, follow these steps:

1. Create a `.env.local` file in the root directory of the project.

2. Add your Clerk and Stream API keys to the `.env.local` file:

   ```
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY= # Your Clerk Publishable Key
   CLERK_SECRET_KEY= # Your Clerk Secret Key
   STREAM_API_KEY= # Your Stream API Key
   NEXT_PUBLIC_STREAM_API_KEY= # Your Stream API Key
   STREAM_CHAT_SECRET= # Your Stream Chat Secret
   ```

3. Start the development server:

   ```
   npm run dev
   ```

   Your application will be available at `http://localhost:3000`.

## Environment Variables

Ensure you have the following environment variables set in your `.env.local` file:

- `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY`: Your Clerk Publishable Key
- `CLERK_SECRET_KEY`: Your Clerk Secret Key
- `STREAM_API_KEY`: Your Stream API Key
- `NEXT_PUBLIC_STREAM_API_KEY`: Your Stream API Key
- `STREAM_CHAT_SECRET`: Your Stream Chat Secret

## Additional Information

- **Stream:** Stream is used for real-time chat functionalities. Make sure to configure your Stream account and obtain the necessary API keys.

- **Clerk:** Clerk is used for user authentication and management. Create a Clerk application and obtain the publishable and secret keys to integrate with this project.

- **Next.js:** Next.js is a React framework for production. It enables server-side rendering and generating static websites for React-based web applications.

- **TailwindCSS:** TailwindCSS is a utility-first CSS framework. It allows for rapid UI development with its predefined classes.
