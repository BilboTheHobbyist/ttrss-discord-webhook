# ttrss-discord-hook
## what it does

A fork of [danirod's plugin](https://git.danirod.es/ttrss-discord-webhook.git) for TinyTinyRSS that adds a filter action so that new items received by feeds can be sent as links to a Discord webhook previously configured in the settings.

I wanted to use it with a recent TinyTinyRSS version, so I shamelessly copied code from tt-rss-yourls' plugin](https://github.com/joshp23/tt-rss-yourls/) and pasted it where I could.

According to danirod, this was a very WIP plugin to start with. I didn't improve anything, so use under your own risk.
## how to install
Copy the discord_hook directory to your plugins.local/ directory in your TinyTinyRSS install.

This plugin will use discord urls as labels. Such labels are potentially wider than the regular ones. Therefore you may customize the theme you are using with the content of the custom.css file.

If you are using Docker builds, you can also bind the directories or something like that.