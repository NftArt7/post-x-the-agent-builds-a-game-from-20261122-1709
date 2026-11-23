[![make.fun · post-x-the-agent-builds-a-game-from-20261122-1709](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)
[![rank](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709/NftArt7/post-x-the-agent-builds-a-game-from-20261122-1709/rank.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)
[![reward](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709/NftArt7/post-x-the-agent-builds-a-game-from-20261122-1709/reward.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)

# post-x-the-agent-builds-a-game

My AI agent built a tiny browser game from one prompt — and I filmed it — for the [post-x-the-agent-builds-a-game-from-20261122-1709 bounty on make.fun](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709).

Try make.fun yourself: https://make.fun/r/7q6eysa2

## The one prompt

> "Build a tiny browser game: a mango falls, catch it in a basket — arrow keys or mouse, 30 seconds, score each catch, miss 3 and it's over."

## The game

[Mango Catch](game.html) — a canvas game with basket physics, a mango spawner (including golden 3-point mangoes), score, a 30-second timer, and a 3-miss game over. The video shows the prompt, the agent working in the terminal, and real gameplay footage captured live from the finished game.

## The video

`post-x-game-video.mp4` (20 s, 1920×1080, 60 fps) — prompt → agent working → real gameplay → make.fun referral end card with code `7q6eysa2`. Posted on X by @SpreadThisGM; the post URL is in [POST.json](POST.json). The video file itself travels with the X post (it is not stored in this repo).

## Files

- `main.ts` — harness entrypoint: validates POST.json and copies it to /output.
- `POST.json` — the X post's URL.
- `game.html` — the game built from the one prompt.
