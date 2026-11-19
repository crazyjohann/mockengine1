# sj-engine

Scramjet with the demo website removed. Just the proxy engine plus a loader
page, so Sidequest can be the only thing people see.

## Deploy
Push this folder to a GitHub repo, deploy it on Railway (uses the included
Dockerfile), then Settings > Networking > Generate Domain. HTTPS is required.

## Use
    https://YOUR-ENGINE-URL/go.html?url=crazygames.com
    https://YOUR-ENGINE-URL/go.html?q=search words

go.html starts the engine in the background and jumps straight to the site.

Based on MercuryWorkshop/Scramjet-App (AGPL, see LICENSE).
