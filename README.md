# Star Year

A daily journal that grows into a memory sky.

Inspired by the One Year app, but instead of a garden of flowers, each day you plant a star. Over the year your sky fills with constellations of memories.

## Features

- **Memory Sky**: 365 days visualized as stars. Better structured home with monthly progress cards and a clean grid.
- **Day Cards**: Swipe-style view of individual memories with text, photos, and doodles.
- **Plant a Star**: Write, add media, doodle your own star, then plant it with a Dynamic Island-style confirmation.
- **4 Themes**: Night, Day, Cosmic, Amber — all with the sketchy doodle aesthetic (Caveat font + imperfect shapes).
- **AOD Mode**: Landscape-style always-on star field (tap to exit).
- **Plans**: Subscription UI matching the original Naira pricing.
- **Seamless improvements**:
  - Clear monthly progress on the home screen
  - Prominent "plant today's star" CTA
  - Theme switcher
  - Island notifications for actions (planting, reminders)
  - Cleaner information hierarchy than a pure dot grid

## Tech

- React + TypeScript + Vite
- Tailwind CSS
- Framer Motion
- Lucide icons

## Run

```bash
npm install
npm run dev
```

Then open the local URL. Designed mobile-first (best viewed in a narrow viewport or device mode).

## Notes

This is a high-fidelity visual and interaction prototype. Persistence, real media, drawing canvas, and backend sync would be added for a production version. The Dynamic Island experience is custom-built (inspired by islandcn concepts) and shows contextual feedback at the top of the screen.
