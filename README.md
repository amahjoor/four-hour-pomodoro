# 240-minute pomodoro with brown noise

A Next.js 14 page with one timer: 240 minutes of work, then 55 minutes of break, then work again. The heading on the page is "lock in." Click the timer button to start or pause. The corner button points an `<audio>` tag at `/audio/brown-noise.mp3`. The file in the repo is `src/app/audio/brown-noise.mp3`, which Next.js does not serve at that URL, so the button will not find the clip until the file is placed in `public/audio/`.

```bash
npm install
npm run dev
```

Open http://localhost:3000. `npm run dev` is Next.js 14.2.

## License

[MIT](LICENSE)
