# Nazar Falach

**Full-stack developer — TypeScript, Node.js, React / Next.js.**
I build web services end to end: the API, the background jobs behind it, the UI on top, and the CI and Docker setup that ship it.

🌐 [falach.pl](https://falach.pl)

## Featured project

### [PulseGuard](https://github.com/Tedossss/PulseApiGuard): API uptime monitoring

Users register HTTP endpoints. Workers check them on a schedule and record latency and uptime. After three failures in a row the endpoint is marked as down, and an alert goes to Telegram.

- **Backend:** strict TypeScript, Express, MongoDB, BullMQ job schedulers, and Redis locks so that only one worker checks a given monitor at a time
- **Security:** SSRF protection checks addresses after DNS resolution, sessions use HttpOnly cookies, rate limits are stored in Redis, every route checks ownership
- **Frontend:** Next.js and React dashboard with Recharts trends and cursor-paginated check history
- **Quality:** unit tests and API integration tests against real MongoDB and Redis, CI, Docker Compose

[Live demo](https://falach.pl/dashboard?demo=1) · [Code](https://github.com/Tedossss/PulseApiGuard)

## Also on GitHub

- [codex-usage](https://github.com/Tedossss/codex-usage): KDE Plasma 6 widget and tray app for Codex usage limits on Arch Linux (Python, QML)

## Stack

`TypeScript` `Node.js` `Express` `React` `Next.js` `MongoDB` `Redis` `BullMQ` `Docker` `GitHub Actions` `Python`

## Open to

Full-stack and backend roles. The best way to reach me is through [falach.pl](https://falach.pl).
