# screen-sharing-web-app
[![Build](https://github.com/notHyotic/screen-sharing-web-app/actions/workflows/build.yml/badge.svg)](https://github.com/bnlabs/mello/actions/workflows/build.yml)

# Run Locally
``` 
git clone https://github.com/notHyotic/screen-sharing-web-app.git
cd screen-sharing-web-app
pnpm install
```

Go to https://livekit.io/, create an application and retrieve the api key, api secret, and live kit websocket link. Then set the the appropriate environment variable, follow `example.env`


```
pnpm run dev
```

# Self Hosting
With a github account, this can be hosted for free with [Vercel](https://vercel.com/)