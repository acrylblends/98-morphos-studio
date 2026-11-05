# MorphOS Studio

A sandbox for inspecting adaptive interfaces, runtime-generated tools and configuration changes.

An ACRYL Blends blueprint for the **Self-modifying / Adaptive** category (`acrylblends.morphos-studio`, category 98 of 100).

Status: designed, being built. `design/spec.md` is the specification and `design/mockup.html` the mockup (open it in a browser). The app itself,
composed from Cordis plugins (one `plugins/<feature>/` folder and one `blend.yaml` row per feature), lands here when it passes review.

When it is ready you will start it with:

```sh
npm create acrylblends@latest my-app -- --from acrylblends.morphos-studio
cd my-app && npm install && npm run dev
```

Listed on https://acrylblends.github.io/blends and https://acryl.dev/blends.
