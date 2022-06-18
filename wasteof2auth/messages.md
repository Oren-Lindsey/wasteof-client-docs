# wasteof2auth messages

- get unread messages `wasteof2.getUnreadMessages(page)`: gets your unread messages, paged

    options: page (page of messages)
- get read messages `wasteof2.getReadMessages(page)`: gets your read messages, paged

    options: page (page of messages)
- mark messages as read `wasteof2.markAsRead(messages)`: marks messages as read

    options: messages (array of message ids, ids can be obtained from getUnreadMessages or getReadMessages)
- mark messages as unread `wasteof2.markAsUnread(messages)`: marks messages as unread

    options: messages (array of message ids, ids can be obtained from getUnreadMessages or getReadMessages)
- get message count `wasteof2.getMessagesCount()`: gets the number of messages you have

    options: none