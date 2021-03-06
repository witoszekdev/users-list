Example Users list app that fetches data from [JSON Placeholder API](https://jsonplaceholder.typicode.com/)

![App Preview Screenshot](/docs/app_preview.png)

## Live Demo

App is automatically deployed to Vercel on every push to main.
[See it live](https://users-list-taniotanio7.vercel.app/)

## Run locally

Make sure Node >= 12 is installed as well as npm or yarn

```
yarn
yarn dev
```

or using npm:

```
npm install
npm run dev
```

## Tech stack

Website uses following tech stack:
- TypeScript
- [Next.js](https://nextjs.org/) - React.js framework
- [Tailwind CSS](https://tailwindcss.com/) - for default styles
- [twin.macro](https://github.com/ben-rogerson/twin.macro) + [Emotion](https://github.com/emotion-js/emotion) - for CSS-in-JS

Additional packages:
- [react-content-loader](https://github.com/danilowoz/react-content-loader) - for building loading skeleton
- [use-http](https://use-http.com/#/) - for useFetch hook

## Lighthouse Score

Thanks to Next.js brilliant defaults, the app scores 100 points in Lighthouse test

![Lighthouse Score](/docs/lighthouse_score.png)