# Vocab Conquest

AP World vocab flashcards (spaced repetition, drills, territory map). Single static page in `public/index.html`, exported from the Claude artifact.

Progress is saved in the browser's localStorage. The Claude account sync only runs inside claude.ai, so on the hosted site each browser keeps its own progress (use the backup/export box to move it).

## Run locally

```
npm install
npm run dev
```

## Deploy to Cloudflare Pages

```
npx wrangler login
npm run deploy
```

First deploy creates the `vocab-conquest` project → https://vocab-conquest.pages.dev

Custom domain: Cloudflare dashboard → Workers & Pages → vocab-conquest → Custom domains (domain must be on Cloudflare).
