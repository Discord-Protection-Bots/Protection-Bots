# This page is under construction- Please forgive any spelling or other errors. 

## What are The Protection Bots

### Introduction

#### The Protection Bots are a group of bots designed to protect discord servers from certain attack Vectors by use of algorythems,
-   using a blacklist built by the bot and other servers to help keep spamming and hacking activities to a minimum.
-   protect against link spamming
-   Protect against Server invite spamming
-   Backup server structure and permissions
-   Backup a users permissions to the server
-   Re-apply permissions to a person if they rejoin the server (optional)

### Permissions
- ![image](https://github.com/user-attachments/assets/6d032cf1-755b-4d7c-b9f7-517cd4f33819)

#### Permission Faq
#####
- Can Protection bot kick or ban users?
--   Yes Protection can kick or ban any users that exist below the level of the bot
- What Level Should the bot be in the permission list?
--   The Bot Should exist directly below the owner of the server (at the top of the list)
- Can the Bot Read Messages in my Channels?
--   Yes The bot can read messages in all the channels you give it permission to, We recommend allowing the bot to work in all channels
- Can I limit what channels the bot has access to see?
--   You may invite the bot, without any permissions and specify what permissions it has manually
- What does the bot do with messages that it reads?
--   The bot ignores all messages that do match a certain criteria, and the based on what the message says if it meets the criteria, the bot will determine if this is one of the items to watch for.
- What does the bot store from my server.
--   Only information stored is your settings so they can be refrenced if the need arizes.

  


#### Discord Link Spamming, 
##### When a user Joins a server and Spams Links to multiple channels that may contain an attack and there are no admins around, The bot will detect this action and through propriatery algorythims and determine if a user trips the alarm threshold depending on the alamr detected
they will be timed out or banned From the server. This action may add them to the blacklist and the bots may prevent that user from rejoining a server

#### Discord Server Spamming
##### When a user Joins a server and Spams Links to multiple channels that may contain an attack and there are no admins around,
The bot will detect this action and through propriatery algorythims and determine if a user trips the alarm threshold depending on the alamr detected

#### Takeover Attack
##### The bot will allow a Server Owner to specify certain users as trusted admins the users will have the ability to Register Their account for protection. If an account is protected and the proper setup is adheard to if the user is kicked or banned,
The bot will take the following actions,
-   Set the User that kicked or banned the admin to a specified permission and remove all others
-   Remove any ban placed on the user
-   Re-add the user to the discord server
-   Apply Permissions granted that users from the last server backup
-   Alert the admin channel as to the incident

