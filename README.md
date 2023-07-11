# Next.js Clerk Authentication App

A Next.js app that uses [Clerk](https://clerk.com) for authentication and user management.

## Usage

Go to your https://clerk.com dashboard and click on `Developer->API Keys` to copy your keys. Create file named `.env.local` and add the below variables 

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=YOUR KEY
CLERK_SECRET_KEY=YOUR KEY
```


Install the dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Access [http://localhost:3000](http://localhost:3000) with your browser.
