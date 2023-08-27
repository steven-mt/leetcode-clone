# LeetCode Clone

This project follows the [LeetCode clone made by burakorkmez](https://github.com/burakorkmez/leetcode-clone-youtube), made in TypeScript with Next.js, Tailwind CSS, and Firebase.

## Features

- Log in and sign up using email and password, with forgot password option (Firebase authentication)
- If a user is logged in and tries to visit the login/sign-up page, they will be redirected to the main page instead
- View problems without logging in, while submitting the code requires the user to be logged in
- Keep track of data for problems and users (data stored in Firestore)
  - Each user has a list of liked, disliked, and starred problems, as well as the problems they have solved
  - Each problem has a like and dislike count
- Resize description, code editor and test case panes

## Getting Started (Development)

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
