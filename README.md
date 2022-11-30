
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
