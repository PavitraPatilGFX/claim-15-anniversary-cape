# Claim Minecraft 15th Anniversary Now!
Hello, Guys This is a Documentation of How to Get 15th Anniversary Minecraft Cape for free, after it's gone

## Steps
> [!NOTE]
> you need to sign in with your correct Minecraft account in the website.

1. Open this official Minecraft Site.
2. Right Click and go to Inspect.
3. Click on Console
4. Paste this code ↓ and click enter.

```
const mcToken = JSON.parse(localStorage.getItem('MCTokenconst mcToken = JSON.parse(localStorage.getItem('MCToken')).mcToken;
 
fetch("https://net.web.minecraft-services.net/api/v1.0/grant/offer?offer=7118a7d5-240e-4f6d-8959-5269ba041938", {
  "headers": {
    "accept": "/",
    "accept-language": "en-US,en;q=0.9",
    "authorization": mcToken,
    "content-type": "application/json",
    "priority": "u=1, i",
    "sec-ch-ua-mobile": "?0",
    "sec-ch-ua-platform":"Windows",
    "sec-fetch-dest": "empty",
    "sec-fetch-mode": "cors",
    "sec-fetch-site": "cross-site"
  },
  "referrer": "https://www.minecraft.net/",
  "referrerPolicy": "strict-origin-when-cross-origin",
  "body": null,
  "method": "PUT",
  "mode": "cors",
  "credentials": "include"
})
.then(response => {
    console.log('Status Code:', response.status);
  })

```
5. After type `allow pasting`
   
