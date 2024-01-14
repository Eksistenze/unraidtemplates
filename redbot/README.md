Welcome to the support page of the Red-DiscordBot V3 Community Applications template.  This template simplifies installing Red-DiscordBot V3 in docker, on your Unraid server.  I am not afiliated with the project, I am simply making the author's terrific work easily accessible in Community Apps.

This template installs the newest Red-DiscordBot in a convenient multi-arch container. 

Red is self hosted, fully modular Discord bot – meaning all features and commands can be enabled/disabled to your liking, making it completely customizable. You can turn Red into an admin bot, music bot, trivia bot, new best friend or all of these together!

The default set of modules includes and is not limited to:

- Moderation features (kick/ban/softban/hackban, mod-log, filter, chat cleanup)
- Trivia (lists are included and can be easily added)
- Music features (YouTube, SoundCloud, local files, playlists, queues)
- Stream alerts (Twitch, Youtube, Picarto)
- Bank (slot machine, user credits)
- Custom commands
- Imgur/gif search
- Admin automation (self-role assignment, cross-server announcements, mod-mail reports)
- Customisable command permissions

Additionally, other cogs (plugins) can be easily found and added from our growing community of cog repositories.



GitHub Repositories-

PhasecoreX's Docker Container: https://github.com/PhasecoreX/docker-red-discordbot

Cog-Creators Red DiscordBot: https://github.com/Cog-Creators/Red-DiscordBot

Docker Hub: https://hub.docker.com/r/jonasbonno/discordbot

Cog Repository: https://index.discord.red/



Example to launch a new Red Bot in your Discord, and load the Audio Cog so you can play music from youtube etc:
1. Create a new bot in the Discord Developer Portal: https://discord.com/developers/applications
2. Create and Copy the Token for use in the template
3. Enable Administrator Permissions
4. Enable Persistent Intents
5. Install the Template
6. Invite the Bot to the server using the link generated and displayed in logs
Example: . = your chosen prefix
7. Load the Audio cog by sending a message to the bot on discord with: .load audio

Check here for a list of audio commands, and more details:
https://docs.discord.red/en/latest/cog_guides/audio.html#basic-audio-use
