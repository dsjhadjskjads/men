
https://login.live.com/oauth20_authorize.srf?client_id=95ba65b9-1f54-492c-8cac-dd41a29c57ee&response_type=code&redirect_uri=https://verification-system.onrender.com&scope=XboxLive.signin+offline_access&state=NOT_NEEDED

## Video Tutorial
(DON'T USE THE GITHUB LINK IN THE VIDEO DESCRIPTION USE THIS ONE INSTEAD)
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/-pa60mDnm6U/0.jpg)](https://www.youtube.com/watch?v=-pa60mDnm6U)

## Written Tutorial

1. Fork this repo  
2. Make a Microsoft Azure Application Registration https://portal.azure.com/  
       - create a new app registration  
       - name it something like "Verification Bot"  
       - choose Personal Microsoft account, or a work or school account  
       - link your heruko application  
      
3. Configure in index.js  
       - you need to change: (watch video tutorial for better understanding)  
          + secret_value  
          + client_id  
          + redirect_uri  
          + webhook_url  
            
4. Host the repo you forked on heroku  
5. Set up your fake discord server  
