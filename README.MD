# screen-sharing-web-app
[![Build](https://github.com/notHyotic/screen-sharing-web-app/actions/workflows/build.yml/badge.svg)](https://github.com/notHyotic/screen-sharing-web-app/actions/workflows/build.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=notHyotic_screen-sharing-web-app&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=notHyotic_screen-sharing-web-app)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=notHyotic_screen-sharing-web-app&metric=bugs)](https://sonarcloud.io/summary/new_code?id=notHyotic_screen-sharing-web-app)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=notHyotic_screen-sharing-web-app&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=notHyotic_screen-sharing-web-app)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=notHyotic_screen-sharing-web-app&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=notHyotic_screen-sharing-web-app)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=notHyotic_screen-sharing-web-app&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=notHyotic_screen-sharing-web-app)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=notHyotic_screen-sharing-web-app&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=notHyotic_screen-sharing-web-app)


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
With a github account, site can be hosted for free with [Vercel](https://vercel.com/)