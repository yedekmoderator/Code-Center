#What is this server?
This is the Discord API server (guild). Here, we focus on the technical aspects of the Discord API and SDK; the interfaces, code, and tools used to interact with Discord's servers (back-end devices). Generally, this refers to writing and developing OAuth applications (including bots) and the wrappers or libraries that facilitate this. You may also find general programming discussions or casual discussions unrelated to the API, but those are not necessarily our main focus. Please make sure you are familiar with our #rules before participating.

Is this an official Discord server?
No. You may find Discord staff lurking here or you may get directed here by them, but Discord API is not an official server. While we do make every attempt to maintain a high standard of integrity and accuracy, there is no guarantee that what goes on here is officially approved by Discord. Similarly, all interpretations of any legal or non-legal documentation provided here are not official.

What is the Discord API?
The Discord Application Programming Interface allows users to communicate and interact with Discord. Both the official Discord client(s) and user-created applications use the same API, but in different ways.

What is the Discord SDK?
The GameBridge Software Development Kit allows game developers to integrate Discord services into their games and other applications.

Where can I learn more about the Discord API or SDK?
The best place to start is the official documentation at https://discordapp.com/developers/docs/intro. If you have questions about the documentation or about direct use of the Discord API, or if you would like to contribute to the documentation, you can visit the GitHub page at https://github.com/discordapp/discord-api-docs or our #api channel. Please remember that off-topic discussion is strictly forbidden in these places.

What is an OAuth (or OAuth2) application (or app)?
Discord allows users to register applications in association with their regular account. These applications can be used to automate certain actions that would be tedious to do manually. For example, a developer may want to allow users to access their website using their Discord accounts. OAuth provides a secure way of doing this.

What is a Discord bot?
A bot is a special type of automated user account that has its own set of privileges and restrictions. Bots are displayed with a "BOT" tag in the Discord client, and can only be managed over the API, not by using the regular Discord client. A bot is always associated with an OAuth application, and it is invited to servers using an OAuth2 authorization flow (see How do I add a Discord bot to my server?). Regular users cannot currently be converted into bot users and vice versa.

How do I make a Discord bot?
Since code is required to run a bot, we very strongly recommend that you have some programming experience before making your own. Note that code is executed and a bot is the product of that code; a bot is not something into which code is loaded, and a bot will not automatically do anything unless you program it accordingly. With some programming knowledge, the first step to developing a bot is to create a new application at https://discordapp.com/developers/applications/me. You should then read the documentation regarding the Discord API on the same site. Following that, you may want to pick a community-supported API library in a programming language of your choice. Each library will have its own set of documentation and instructions for developing applications, which you should read and follow before writing your bot code.

How do I add a Discord bot to my server?
Bots are added to a server with an OAuth2 URL https://discordapp.com/api/oauth2/authorize?client_id=CLIENTID&scope=bot&permissions=0 where CLIENTID is replaced by your (or someone else's) bot's Client ID. This number is found on the bot's application page at https://discordapp.com/developers/applications/me. Permissions can be omitted, but if you want the bot to join a server with pre-determined permissions, you will need to include a value. Use this calculator to determine the correct value: https://discordapp.com/developers/tools/permissions-calculator. Alternatively, you can use this tool to generate an OAuth2 URL: https://discordapp.com/developers/tools/oauth2-url-generator. Be sure to select the bot scope.

What is a wrapper/library?
Several members of the Discord community have written and may currently maintain software libraries that serve as wrappers for the Discord API. These libraries facilitate interaction with the Discord API by providing user-friendly interfaces in your favorite programming languages. This server hosts a collection of libraries that are considered fully-featured and well-suited for public use. You can find more information about this in the #info channel.

Can I write my own library?
Generally, there is at least one Discord API library already written for the more popular, modern programming languages. We recommend that you use these pre-existing libraries, and contribute to them if possible. If you find that these libraries are not sufficient, feel free to write your own, especially if one does not exist for the language that you want to use.

Can I get a channel for my own library here?
You must have a complete library before we can consider including it here. For a detailed explanation regarding what we consider good enough for consideration, please read https://gist.github.com/meew0/bbbbd5348967dee5f7e84c0cd58983fd.

What roles does this server have?
The main roles here are Admin, Mods, Library Devs, Contributors and Proficient:

Admin: Users who are responsible for general maintenance of the server and decision making.
Mods: Users who are responsible for enforcing server rules and making sure everyone is doing what they should be doing, in the right places.
Library Devs: Authors and maintainers of the community-supported API libraries that are featured here.
Contributors: Major contributors to the community-supported API libraries that are featured here.
Proficient: Minor contributors to the community-supported API libraries that are featured here and users who are experienced Discord API users.
Can I add my bot here?
Discord API is generally not a place to feature user-made bots, but if you think that you need to add your bot to the server for testing, DM a moderator with a link to invite the bot with no permissions, a brief summary of what the bot does, and a brief summary of why you need the bot on this server. Your bot will be restricted from certain channels. If you want to show your bot to an audience, consider adding it to the Discord Bots server instead. An invite link for this can be found in #info.

Where can I find help for something that is not Discord API related?
Although you may find help for minor issues here, we are not inclined to assist with official Discord related issues.

If you need to contact Discord, visit their support page at https://support.discordapp.com/hc/en-us, submit a request at https://support.discordapp.com/hc/en-us/requests/new, or send a tweet at https://twitter.com/discordapp.
If you need to report a bug with an official Discord client, visit https://discord.gg/discord-testers
If you want to recommend or criticize Discord features, visit https://discord.gg/discord-feedback
Are "selfbots" or "userbots" allowed?
Automating user accounts as "selfbots", "userbots", or any applications outside of the OAuth API is forbidden by Discord. Be smart and use a proper bot account.

Does Discord not tolerate certain selfbot uses?
Discord does not tolerate inappropriate use of its API. If Discord thinks that their API is being used in a way that they consider to be inappropriate, the associated account(s) may be restricted from accessing the API.
