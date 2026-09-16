# DZS Commission Bot V5

FIXED VERSION:
- Slash commands register automatically after bot login.
- CLIENT_ID is no longer required.
- If GUILD_ID is set, commands are registered instantly in that server.
- If GUILD_ID is empty, commands are registered to every server the bot can see.
- Clear Railway logs for missing/wrong environment variables.
- Skin 64/128/512, Render, Logo, Animasi.
- Sequential DZS-0001 order numbers.
- Private tickets, worker claim, status buttons.
- Completed ticket gives customer 1-5 star rating.
- Feedback post shows Worker, Reviewer, Rating, Review/Ulasan.

Railway Variables required:
DISCORD_TOKEN
GUILD_ID (recommended)
TICKET_CATEGORY_ID
FEEDBACK_CHANNEL_ID
LOG_CHANNEL_ID
STAFF_ROLE_ID

IMPORTANT:
1. DISCORD_TOKEN must be the BOT TOKEN from Discord Developer Portal.
2. Do not put Client ID into DISCORD_TOKEN.
3. Invite the bot with bot + applications.commands scopes.
4. Bot needs View Channel, Send Messages, Embed Links, Read Message History,
   Manage Channels, Manage Messages.
5. Mount a Railway Volume at /app/data if you want SQLite data to survive redeploys.
