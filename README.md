# 🎉 Claim the Minecraft 15th Anniversary Cape for Free!  

This guide explains how to claim the **Minecraft 15th Anniversary Cape** even after the official event ends.  

## ⚠️ Important Note  
> **Ensure you are signed in with the correct Minecraft account** before proceeding.  

## 📌 Steps to Claim the Cape  

1. Open the official [Minecraft 15th Anniversary website](https://www.minecraft.net/en-us/15th-anniversary).  
2. **Right-click** anywhere on the page and select **Inspect** (or press `F12`).  
3. Navigate to the **Console** tab.  
4. Paste the following code into the console and press `Enter`:  

```javascript
const mcToken = JSON.parse(localStorage.getItem('MCToken')).mcToken;

fetch("https://net.web.minecraft-services.net/api/v1.0/grant/offer?offer=7118a7d5-240e-4f6d-8959-5269ba041938", {
  "headers": {
    "accept": "*/*",
    "accept-language": "en-US,en;q=0.9",
    "authorization": mcToken,
    "content-type": "application/json",
    "priority": "u=1, i",
    "sec-ch-ua-mobile": "?0",
    "sec-ch-ua-platform": "Windows",
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
});
```

5. Type `allow pasting` in the console if prompted.  
6. Wait **10 to 45 minutes** for the cape to appear in your Minecraft profile.  



## ❓ FAQ  

### How long does it take to receive the cape?  
You will receive the cape within **10 to 45 minutes**.  

### Will I receive the cape in both Java and Bedrock?  
Yes, the cape will be available in **both editions**.  

### I only own one edition. Will I still get the cape?  
Yes, you will receive the cape in the edition you own.  

### Can my account get banned for this?  
No, **Mojang is aware of this method** but has not patched it. Since this cape is part of the **15th Anniversary Celebration**, Mojang will not ban any accounts for claiming it.  
