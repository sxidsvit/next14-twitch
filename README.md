# Fullstack Twitch Clone


###  Next.js 14, Livestreaming, React, Prisma, Stripe, Tailwind, MySQL


- Streaming using RTMP / WHIP protocols 
- Generating ingress
- Connecting Next.js app to OBS / Your favorite streaming software 
- Authentication 
- Thumbnail upload
- Live viewer count 
- Live statuses 
- Real-time chat using sockets 
- Unique color for each viewer in chat 
- Following system 
- Blocking system 
- Kicking participants from a stream in real-time 
- Streamer / Creator Dashboard 
- Slow chat mode 
- Followers only chat mode 
- Enable / Disable chat 
- Collapsible layout (hide sidebars, chat etc, theatre mode etc.) 
- Sidebar following & recommendations tab 
- Home page recommending streams, sorted by live first 
- Search results page with a different layout 
- Syncing user information to our DB using Webhooks 
- Syncing live status information to our DB using Webhooks 
- Community tab 
- Beautiful design
- Blazing fast application 
- SSR (Server-Side Rendering) 
- Grouped routes & layouts 
- MySQL
- Deployment

### Prerequisites

**Node version 18.17 or later**

### Cloning the repository

```shell
git clone https://github.com/sxidsvit/next14-twitch-clone.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
CLERK_WEBHOOK_SECRET=

DATABASE_URL=

LIVEKIT_API_URL=
LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_WS_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
```

### Setup Prisma

Add MySQL Database (I used PlanetScale)

```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
npm run dev

```

---

##### Contact with me: 
[<img alt="webDev | LinkedIn" src="https://img.shields.io/badge/linkedin-0077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />][linkedin]

[linkedin]: https://www.linkedin.com/in/sergiy-antonyuk/

##### I can't express how much I have learned from [you](https://www.youtube.com/@codewithantonio) ! <br> Thanks for the hard and smart work.


![](demo.gif)
