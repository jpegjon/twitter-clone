## Technologies Used

- **[Next.js](https://nextjs.org/)** - Used as the app framework to handle everything from data fetching, rendering, state management etc.
- **[Sanity CMS](https://www.sanity.io/)** - Used as the content platform/database to house the tweets
- **[TypeScript](https://www.typescriptlang.org/)** - Used for strong static typing and help minimize the amount of bugs/warnings in the app.
- **[Tailwind CSS](https://tailwindcss.com/)** - Used to style the app.
- **[Toast](https://react-hot-toast.com/) notifications** - Notifications that display when the feed has been refreshed, or when a new tweet has been posted to the timeline.
- **Next.js Server Side Rendering (SSR)** - Used to fetch the tweets from the Sanity CMS backend.
- **[GROQ](https://www.sanity.io/docs/overview-groq)** - The language used to query the Sanity CMS backend for tweet fetching.
- **[NextAuth](https://next-auth.js.org/)** - Used to authenticate a logged in user via the Twitter API.
- **[Vercel](https://vercel.com/dashboard)** - Used as the deployment platform.

## Features & User Flow

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example) or preview live with [StackBlitz](https://stackblitz.com/github/vercel/next.js/tree/canary/examples/with-tailwindcss)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-tailwindcss&project-name=with-tailwindcss&repository-name=with-tailwindcss)

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example with-tailwindcss with-tailwindcss-app
# or
yarn create next-app --example with-tailwindcss with-tailwindcss-app
# or
pnpm create next-app -- --example with-tailwindcss with-tailwindcss-app
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).
