# A list of all changes starting from 08-22-23 and forward.
# Most things before would be stuff just from when Loke was also working on this particular fork of the code before it went private.
# 08-22-23
1. Added a startup message to steam and discord whilst the bot is booting up.
2. Added an embed for the "this bot is still booting up please wait" message on discord.
3. All instances of "TF2Autobot-neko" now have "-Neko" capitalized.
4. Rich Presence now supported for TF2. 
5. States like halt and update are now indicated on steam too.
# 09-04-23
1. Logs now format as [ YEAR-MM-DD HH:MM:SS ] [ LEVEL ]: instead of YYYY-MM-DD HH:MM:SS LEVEL:
# 09-08-23
1. Added autobump into the code, as well as parameters autobump.enable & autobump.interval + some TF2AB-NL formatting (Neko-a-b)
# 09-11-23
1. Uptime now supports showing the system uptime as well.
# 09-26-23
1. Added a PM2 command to allow for better control over the bots.
# 10-17-23
1. Fixed a major bug involving embeds and a lack of a discord token.
2. Previous Unmentioned Feature: GUI Support in IPC branch of tf2abn fork.
# 10-18-23
1. Added rl for refreshlist as an alias that is abreviated.
2. Optimized some embeds.
3. !links now has embed support for discord.
4. !bump now has embed support for discord.
5. embed iconURL can now be changed as well as embed colors warn, error, ok, and default.
# 10-24-23
1. Patched a legacy fallback bug preventing embeds for working in direct messages.
2. Added an "operator" environment option for use with renting on trade bots based on tf2abn.
    - Operators will be able to execute commannds like !eval and !pm2 while admins will no longer be able to if an operator is defined.
    ## Extended Documentation
        - If an operator is defined, only that operator can access commands that require operator to work.
        - If no operators are defined, all admins can access commands.
# TODOS
1. Add !operator command
