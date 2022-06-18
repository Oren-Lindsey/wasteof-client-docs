# wasteof2auth socket

- listen to the wasteof2 websocket `wasteof2.listen(callback)`: listens to the wasteof2 websocket. accepts one option: callback. 

it will also send one parameter to the callback which has an object containing data about the event

the event data will always have a child called `type`, it can be one of 3 options: `"chat message"` is the type every time a message is sent on wasteof.money/chat, `"connect"` is the type when the socket connects, or `"updateMessageCount"` which is sent when your message count changes. 

it will also have a child called `data` which returns the wasteof2 api's data
- send a chat message `wasteof2.chatMessage(content)`: sends a message to wasteof.money/chat

options: content (content to send, can be html or plain text)
