# Changelog

<!--next-version-placeholder-->

## v0.1.1 (2023-02-05)

### Feature

- added Arthurs replicate model for Rivers images

## v0.1.0 (2023-01-02)

### Feature

- added google tts for foreign languages

### Fix

- switched to rivertils 1.7 with google translate


### Tests

- 

## v0.1.0 ()




1.1
refactored replicate request.
clearer print statements so i can make sure it's working properly.
bot now responds with a text message first, with requester name and prompt.
also, noticed that replicate requests included 'show me' so removed that.

1.0.2
refactored on message.
is_message_from_other_guild() now returns a boolean.
delete message based in genreal if image


1.0.1
removed visitor role from neighbors

Added await bad_guild.leave() to on message

Unchecked public bot here:
https://discord.com/developers/applications/890946668940361778/bot

Ok I've successfully migrated to 
https://github.com/Pycord-Development/pycord
pycord (discord2) is a fork of discord.py that is actively maintained.
It still has traditional bot messages.
