# Twitch Clip Rewind
Project for [TimeEnjoyed](https://twitch.tv/timeenjoyed)'s codejam

Look back in **time** at your best stream highlights.

A simple website that "generates" a "rewind" from your most viewed Twitch clips from a specific time period.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

### Requirements 
[NodeJS >=16.14.0](https://nodejs.org/en)

[Twitch client ID and client secret](https://dev.twitch.tv/console/apps/create)

### How to install
```bash
git clone https://github.com/GAMIS65/twitch-clip-rewind.git
cd twitch-clip-rewind
npm install
```

### Configuration
Create a .env.local file in the root folder of this project like below, and enter your Twitch client id/secret:
```
CLIENT_ID="your client id"
CLIENT_SECRET="your client secret"
```

### How to run

To run in dev mode:
```bash
npm run dev
```

To run in production mode:
```bash
npm run build
npm run start
```

### Docker:
```bash
docker build -t gamis65-twitch-clip-rewind .
docker run -p 3000:3000/tcp gamis65-twitch-clip-rewind
```