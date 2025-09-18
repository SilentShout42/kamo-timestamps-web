+++
title = "Hi hi!"
date = "2025-09-17T22:12:14-06:00"
showFullContent = true
+++

Kamo Timestamps is a group of Kamogumis that creates timestamps for Kanna's streams. Doing this makes it easier for others to find the many funny, interesting, sweet, sassy, and TSKR moments in each Kanna stream.

If you're interested in helping out, or just interested in the process: read on!

# Kamo Squad timestamping
We create timestamps in two passes:
1. Using Korotagger in the `#timestamps` channel on the [Kamogumi Lounge][kamogumi_lounge] Discord server during Kanna streams.
2. Using the [ts userscript][ts] to adjust timing and edit descriptions.

[kamogumi_lounge]: https://discord.gg/7YPpm6tPu7
[ts]: https://github.com/silentshout42/ts

# Using Korotagger

## Timestamping - for every Kamo
When a stream begins, you'll see an `Active stream set` message with the stream URL. After this, you can begin using other commands to create and adjust timestamps for the current live stream.

`!t`/`!tag <free text>` to create a new timestamp. Korotagger will acknowledge this command with two reacts: ⭐️ can be used by anyone to upvote a tag, and ❌ can be used by the tag creator to remove a tag.

Editing or deleting the message that created a tag will edit or delete the tag in Korotagger.

`!adjust <seconds>` adjusts the time on your own latest tag by the specified number of seconds, which may be negative. You can use this if you know you're ahead or behind of your latest tag and want to shift the timestamp after creating it.

Timing adjustments via Korotagger are less important for Kamo Timestamps, because we do a second pass on everyone's timestamps using [ts][ts] to adjust timing and descriptions before the final timestamps are posted.

Check out the [Korotagger manual][korotagger_manual] for additional Korotagger commands and info.

## One-time configuration - for admins
You only need to follow these steps to setup Korotagger on your own Discord server. If you join us in the Kamogumi Lounge, you can skip these steps!

Invite the Korotagger bot to your server using one of these invite links: [Koro][koro], [Koro 2][koro2], [Toko][toko], [Purin][purin], [Koyo][koyo], [Fuwawa][fuwawa]. Bots from each invite link function the same and have access to the same list of tags, so pick the name you like best, or try a different link if you run into a message about the bot being in too many servers.

In the channel where you want to timestamp Kanna streams, run `!sub add UClxj3GlGphZVgd1SLYhZKmg`. From now on, the bot will post a message in your timestamps channel every time a live stream begins, and anyone can use Korotagger bot commands to record timestamps.

You can get support for Korotagger in the `#korotagger` channel on the [Hololive Creators Club][hololive_creators_club] Discord. Korotagger source code is at [Yarn/korotagger][korotagger_github].

[koro]: https://discord.com/api/oauth2/authorize?client_id=712957753492111380&scope=bot&permissions=34359856192
[koro2]: https://discord.com/api/oauth2/authorize?client_id=873924260874297354&scope=bot&permissions=34359856192
[toko]: https://discord.com/api/oauth2/authorize?client_id=969027070124507188&scope=bot&permissions=34359856192
[purin]: https://discord.com/api/oauth2/authorize?client_id=1069400081830260756&scope=bot&permissions=34359856192
[koyo]: https://discord.com/api/oauth2/authorize?client_id=1140550575801511936&scope=bot&permissions=34359856192
[fuwawa]: https://discord.com/api/oauth2/authorize?client_id=1258295784730923038&scope=bot&permissions=34359856192
[hololive_creators_club]: https://discord.com/invite/C8McwUd2eD
[korotagger_github]: https://github.com/Yarn/korotagger
[korotagger_manual]: https://563563.xyz/korotagger/

# Using the ts userscript
WRITEME
