# VoiceNotify

VoiceNotify is a Discord bot that notifies people when a voice chat is taking place.

[Add to Discord](https://discord.com/oauth2/authorize?client_id=712670038267789352&scope=bot&permissions=150528)  •  [Self-hosting](https://github.com/vpctorr/DiscordBots/blob/master/VoiceNotify/README.md)

### How to use the bot ?

Bot commands to enable & disable voice chat notifications (administrators only) :

`@VoiceNotify enable [threshold] [roles]`

Enables voice chat notifications for the voice channel you are in, alerts will be sent to the channel where this command is executed.

Optional : [threshold] to trigger an alert defaults to 5 people ; [roles] will be mentioned when the alert is sent.
                
`@VoiceNotify disable`

Disables voice chat notifications for the voice channel you are in.

---

# MakePDF

MakePDF is a Discord bot that automatically converts word processing, spreadsheet and presentation documents to PDF.

[Add to Discord](https://discord.com/oauth2/authorize?client_id=689807933415882762&scope=bot&permissions=52224)  •  [Self-hosting](https://github.com/vpctorr/DiscordBots/blob/master/MakePDF/README.md)

### Common formats are supported :

- DOC ; DOCX ; ODT ; RTF
- XLS ; XLSX ; OSD ; CSV
- PPT ; PPS ; PPTX ; PPSX ; ODP

### How does this work ?

Simply add MakePDF to your server. It will automatically convert all supported files to PDF, in all the channels it has access to.

We use the LibreOffice API to convert your files. Files are only temporarily transitting via our server but are not kept after the task is done.

Source code is freely available on Github. For support or feature requests, please use our [Discord server](https://discord.gg/SrGXHcC) or Github issues.
