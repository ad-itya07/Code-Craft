# Code Craft [(LIVE)](https://code-craft-eight.vercel.app/)

Code Craft is a SaaS application that enables users to write, share, and collaborate on **static** code seamlessly. With features like code sharing, starring, commenting, and more, it fosters a vibrant coding community. The application is live at [https://code-craft-eight.vercel.app/](https://code-craft-eight.vercel.app/).

<hr>

## Features

- **Code Sharing**: Write and share your code snippets with the community.
- **Starring**: Show appreciation by starring others' code snippets.
- **Commenting**: Engage in discussions by commenting on shared code.
- **Authentication**: Secure user authentication powered by Clerk.
- **Real-time Database**: Efficient data management using Convex.
- **Payments**: Handle transactions seamlessly with Lemon Squeezy.

<hr>

## Tech Stack

- **Framework**: Next.js 15
- **Language**: TypeScript
- **Database**: Convex
- **Authentication**: Clerk
- **Payments**: Lemon Squeezy

<hr>

## Getting Started

To run the project locally:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/ad-itya07/Code-Craft.git
   cd Code-Craft
   ```

2. **Install dependencies**:

    ```bash
    npm install
    ```

3. **Set up environment variables**:

Create a .env.local file in the root directory and add the following necessary environment variables for Convex, Clerk, and Lemon Squeezy.

    ```bash
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=

    CONVEX_DEPLOYMENT=

    NEXT_PUBLIC_CONVEX_URL=
    ```

4. **Run the development server**:

    ```bash
    npm run dev
    ```
<hr>

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.