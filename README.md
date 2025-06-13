# Social

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Social is a lightweight Twitter-style platform built with Next.js, React, and Prisma. It helps teams learn full‑stack patterns while delivering a familiar microblogging experience.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Setup](#setup)
  - [Simple Mode Setup](#simple-mode-setup)
  - [Advanced Mode Setup](#advanced-mode-setup)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [FAQ](#faq)
- [License](#license)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## Features

- Secure authentication with NextAuth and Prisma
- Real-time notifications for follows, likes, and replies
- Post creation with threaded comments
- User profiles with follow system and avatars
- Image uploads via drag and drop
- Responsive Tailwind CSS design
- RESTful API routes powered by Next.js
- TypeScript for type-safe development

## Demo

![Screenshot](https://user-images.githubusercontent.com/23248726/224405420-03112a76-250a-4283-992c-60e235170678.png)

## Setup

Both simple and advanced setups use environment variables located in `.env.local`.

### Simple Mode Setup

1. **Clone the Repository**
   ```bash
   git clone <repo-url>
   cd social
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Configure Environment**

   ```bash
   cp .env.example .env.local
   ```

   Required variables:

   * `DATABASE_URL=`
   * `NEXTAUTH_JWT_SECRET=`
   * `NEXTAUTH_SECRET=`

4. **Run the App**

   ```bash
   npm run dev
   ```

### Advanced Mode Setup

Use this mode for production deployments. Configure your MongoDB database, update secrets, and adjust any additional environment variables required for your infrastructure. You can enable optional plugins like logging or analytics here.

## Usage

1. Sign up or log in to create an account.
2. Compose a tweet in the form at the top of the home page.
3. Follow other users and interact with their posts via likes and comments.
4. Visit your profile to update your bio, avatar, and cover image.
5. Check the notifications page for real-time updates on activity.

## Deployment

The application works seamlessly on Vercel. Push your repository and click the button below to deploy.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/)

## Contributing

Contributions are welcome! Fork the repo, create a branch, and open a pull request. Please follow the existing code style and include clear commit messages.

## FAQ

1. **What database does Social use?**  
   Social uses MongoDB via Prisma.
2. **How do I change the default secrets?**  
   Edit the values in your `.env.local` file before running the app.
3. **Where can I report bugs?**  
   Open an issue in this repository with steps to reproduce.

## License

This project is licensed under the MIT license.

## Acknowledgements

- [Next.js](https://nextjs.org/)
- [Prisma](https://www.prisma.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- [NextAuth](https://next-auth.js.org/)

## Contact

For help or feedback, please open an issue or contact the maintainer through GitHub.

