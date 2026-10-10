# Image Search App

Search photos from Unsplash and browse them in a responsive gallery with a modal
preview, "Load More" pagination and toast feedback.

**[Live demo]([https://YOUR-NEW-URL.vercel.app](https://goit-react-hw-04-virid-two-69.vercel.app))**


<img width="1046" height="707" alt="SCR-20261010-urdd" src="https://github.com/user-attachments/assets/fbc21329-e024-4a3e-9bb7-2ec956c61df5" />

## Features

- Search Unsplash by keyword
- Gallery grid with modal preview (react-modal)
- "Load More" pagination
- Loading indicator and toast messages for empty input and errors
- [Rate-limit error message: verify and describe]

## Tech stack

React 19 · Vite · Axios · react-modal · react-hot-toast · react-spinners · ESLint

## Getting started

```bash
git clone https://github.com/Full-Stack-Web-Applications/Image_Search_App.git
cd Image_Search_App
cp .env.example .env.local    # add your Unsplash access key
npm install
npm run dev
```

Requires Node.js 20.19+ (check the Vite docs for the exact range).
Get a key at https://unsplash.com/developers.

## Configuration

| Variable | Description |
|---|---|
| `VITE_UNSPLASH_ACCESS_KEY` | Unsplash API access key |

`VITE_` variables are embedded in the client bundle. This app calls Unsplash
directly from the browser (acceptable for a demo-level key); a production
version would proxy requests through a serverless function.

## Limitations and next steps

- No automated tests yet (planned: Vitest + React Testing Library)
- Demo-mode Unsplash rate limit applies
- Accessibility review of the modal and controls pending

## Credits

Photos by [Unsplash](https://unsplash.com) contributors, shown with attribution
as required by the Unsplash API guidelines.

## License

MIT
