# Changelogs

## v2.7.0 - 10/09/2024

## News
- Update server ip (Thanks to @JediFay)


## v2.6.0 - 3/19/2023

## News
- Add `Client.getFriendList` and `Friend.joinRoom` methods 

## Changes
- Fix room playerList

## v2.5.0 - 2/08/2022

## News
- Update the defaults host/ports.

## v2.4.0 - 1/03/2022

## News
- Update API endpoint

## v2.3.0 - 5/15/2021

## News
- Support #chats (who/join/leave/send and receive messages).

## v2.2.0 - 4/28/2021

## News
- Support bot role instead of ~~tokens~~.
- Can't use endpoint's tokens anymore.

## Changes
- [`Client.start`](docs/Client.md#start) no longer use ~~tfmid and token~~ parameters.
- Fix docs typo

## v2.1.0 - 10/28/2020

## News
- Add friends (requestFriendList method/friendList event).


## v2.0.6 - 09/16/2020

## News
- Add [`languageChange`](docs/Client.md#languagechange) event.

## Changes
- Update to the new language system.
- Remove ~~Client.setCommunity~~ and replace it with [`Client.setLanguage`](docs/Client.md#setLanguage).
- Remove ~~Enums.community~~ and replace it with [`Enums.language`](docs/Enums.md#language)

## v2.0.5 - 09/07/2020

## News
- Add Client.joinRoom method.

## v2.0.4 - 09/06/2020

## Changes
- Transformace adds new string `language` to the handshake structure (All previous versions won't work).

## v2.0.0 - 06/29/2020

## News
- Add whisper event.
- Add rawPacket event.
- Add rawTribulle event.
- Add rawOldPacket event.
- Add Client.sendWhisper function.
- Add Client.handleTribulle function.
- Add Client.sendTribullePacket function.
- Add Client.handleOldPacket function.

## Changes
- Remove ~~Client.sendRoomMessage~~ and replace it with [`Room.sendMessage`](docs/Room.md#roomsendmessagemessage)

## v1.0.5 - 06/28/2020

## News
- Add [`RoomMessage`](docs/RoomMessage.md) for room messages.
- Add [`roomPlayerLeft`](docs/Client.md#roomplayerleft) event.

## v1.0.4 - 06/26/2020

## Changes
- Remove crypto from the package becasue it is built-in library.
- Switch http client library from request to node-fetch because it deprecated library.

