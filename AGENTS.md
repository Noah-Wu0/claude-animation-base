# Agent skills

### Issue tracker
Linear team **Noah_Wu**. See `docs/agents/issue-tracker.md`.

### Domain docs
Animation starter forked from JohnHeibel/ClaudeAnimationBase. Primary guide: `ANIMATION_GUIDE.md`. Scenes live in `src/scenes/`.

### Working agreements
- Animation tickets hang on this repo only; do not mix into other product repos.
- Keep `upstream` remote for syncing from JohnHeibel/ClaudeAnimationBase.
- Demo/render must succeed before marking a Linear issue Done.
- Prefer short Chinese status updates in the Coding room.

## Local checklist
1. `npm install`
2. `node render.mjs --clip --out=out/video.mp4` (add `--soft-gl` on headless Linux)
3. Confirm `out/video.mp4` exists
