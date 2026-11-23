# Charla Spanish

A single-file Spanish learning app (A1), published as a Claude artifact:
https://claude.ai/artifact/2SByHvx36sFy9AhAZzAXi3

- `index.html` is the whole app. No build step, no dependencies.
- It runs inside Claude's artifact runtime: `window.claude.use("db" | "user" | "sample" | "tts" | "dictation")`. Every capability is optional and the app must keep working without it (plain browser: localStorage and speechSynthesis).
- Keep it one file. External scripts only from cdnjs, jsdelivr or unpkg with exact versions; fonts only from Google Fonts.
- Merged changes are republished to the artifact by Jon's local Claude session (the cloud agent cannot publish).
