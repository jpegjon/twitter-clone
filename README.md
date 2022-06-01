# [View Demo](https://jpegjon-twitter-clone.vercel.app/)

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

- Click the "Sign in" button on the left-hand nav, and you're directed to sign in using your Twitter account.
- Once signed in, the user is able to type a tweet in the form, attach an image, and submit.
- Fully responsive design, down to mobile.
- Click the arrow icon near the top-center of the screen to trigger the React Hot Toast feature - a confirmation message that the feed has finished updating.
- The existing comments are tied to/reference existing tweets, using Sanity.
- NASA's Twitter feed is embedded on the right-hand nav.
