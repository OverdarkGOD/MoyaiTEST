# MoyaiTEST | Version 0.8
MoyaiTEST is a Discord Bot made in Python. It is the testing bot to our main bot, Moyai. Our testing bot will provide tests to newly added functions. Some functions may or may not work.

# Future Expectations
Our next update will be version 0.9. With the main release of version 0.9, we are wanting to add some functions to better support our users. You will see better moderation support, and better utility support. As of right now, our moderation functions are limited and a bit funky to execute. The plan is to create a better moderation utility. Our SQL functions are also funky to execute too. The functions themselves work, but they show very little output to what has been inputted.

# Current Time
With version 0.8, we have rewrote practically all of Moyai, aside from the sql.py file and the music.py file. We have removed the info.py file and integrated the functions to the support.py file. We have organized miscellaneous functions in their correct categories. We've also integrated OpenAI's gpt-3 API onto Moyai. Making Moyai one of the smartest Discord Bots to hit the platform. As of right now, sql functions and moderation functions will need to be improved for better execution.

# Commands | Example
- COMMAND_IS_HERE: THE DEFINITION OF THE COMMAND
   - PARAMETER_IS_HERE: THE DEFINITION OF THE PARAMETER

## Fun Commands 
   - pong: outputs the bot client latency - Command Works
   
   - avatar: enlarges the pinged user's profile picture - Command Works
      - member: define the user you want to enlarge the profile picture of
      
   - ping: ping an IP/DNS Command Works
      - website: define the IP/DNS you would like to ping
   
   - google: google search within discord - Command Works
      - message: define what you're searching for
   
   - rando: the bot will send a random photo - Command Works
      - message: define what you're searching for
 
   - memes: the bot will send a random meme - Command Works
   
   - openai: gpt-3 API integration within Moyai. 
      - text: define your query so Moyai can respond back to you
 
## Mod Commands
   - purge: allows users with manage permissions to delete previous messages - Command Works
      - amount: define the amount of messages you would like to delete
   
   - warn: allows users with kick or ban permissions to send warnings to users. - Command is being rewritten
   
   - ban: allows users with ban permissions to ban users within a guild - Command Works
      - member: define the user you would like to ban from your guild
      - reason: define a reason for the ban (optional)
      
   - unban: allows users with ban permissions to unban users within a guild - Command Works 
      - member: define the user you would like to unban from your guild
   
   - kick: allows users with kick permissions to kick users within a guild - Command Works
      - member: define the user you would like to kick from your guild
      - reason: define a reason for the kick (optional)
   
   - lock: allows users with manage channels to lock users from texting, sending attachments, and reactions within a channel - Command Works
      - role: choose a role that users have that you'd like to lock
      
   - unlock: allows users with manage channels to unlock users ability to text, send attachments, and react within a channel - Command Works
      - role: choose a role that users have that you'd like to unlock
      
   - clone: allows users with manage channels to automatically delete and recreate a channel - Command Works
      - channel: choose a channel to clone
   
 
## Music Commands
   - join: makes the bot join the voice channel you are currently in - Command Works
   
   - summon: makes the bot join a voice channel you wish - Command Works
      - channel: choose the channel the bot will join 
      
   - leave: makes the bot leave the voice channel - Command Works
   
   - volume: allows users to adjust the volume of the bot's audio output - Command Works
      - volume: adjust the volume using integers
      
   - now: shows the currently playing song - Command Works
   
   - pause: pauses the current song - Command Works 
   
   - resume: resumes the current paused song - Command Works 
   
   - stop: stops playing the song & clears the queue - Command Works 
   
   - skip: vote to skip a song, the requestor can automatically skip. 3 votes needed in order to skip a song - Command Works
   
   - queue: shows the player's queue - Command Works
      - page: queue the song of your choice
      
   - shuffle: randomizes the queue - Command Works
   
   - remove: remove a song from the queue at a given index - Command Works
   
   - loop: loop the currently playing song. Invoke the command again to unloop - Command Works
   
   - play: enter the URL of the song from YouTube and the bot wiull join the voice channel you're in and the bot will automatically start playing the song - Command Works
      - search: choose the song you want to play
   
## SQL Commands
  - create: allows users to create a database table - Command Works
    - table: the name of the table you're creating
    - task:  the task you're creating
    - value1
    - value2 
    - value3
    
  - insert: allows users to insert data by typing in the following parameters - Command Works
    - table: enter the table you're inserting data into
    - task: enter the task you're inserting data into
    - value1
    - value2
    - value3
    
  - delete: allows users to delete a row within a table - Command Works
    - table: enter the table that you're deleting data from
    - task: enter the task you're deleting data from
    - row_x: enter the row you're deleting
    
  - fetch: allows users to fetch all information within a table - Command Works
    - table: enter the table you're fetching
    - task: enter the task you're deleting
    
  - verify: allows users to verify if the table or the SQL module is working correctly - Command Works
    - table: enter the table you're verifying

## Support Commands
- help: displays the Help Manager

- info: shows information about the server

- thread: create a thread in a forum channel

- dm: send a message to a user or yourself
   - member: define the member you are sending a message to
   
- dm_find: fetches the contents from a user's dm
   - member: define the member you are fetching contents from
   
- captcha: user verification upon joining a guild (Command is meant to be used once)

- whois: allows users to see information about a member in a guild
   - member: define the member you are seeking informatiom from
  






