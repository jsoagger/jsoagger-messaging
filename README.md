# soaggy-chat

Chat module for Jsoagger platform.


# General requirements

1. Soaggy chat must be integrated to any JSaoagger applications
2. Soaggy chat backend is a standalone springboot microservice
3. The admin of chat is a person that can manage a chat
4. The chat is always started by the user
5. The admin of a chat can manage mutiple chat
6. If a chat was assigned to an admin, only him can manage it
7. He can assign the chat to another admin.
8. The admin or the user can closes the chat
9. When user starts a chat:
    a. All connected admins ared notified (option modifiable)
    b. The chat is added to non managed chats
    c. A pick button permits to assign the chat to current user
    d. When the chat is assigned, it moves to the board of current user
    e. The board of current user shows all chats of user

# ECOMMERCE CHAT

## Offline chat
Applicable if the web site permit anonymous navigation and anonymous chat.

In this case:
1. The user is unkown (not connected to application)
2. The admin is kown user (connected)
4. Chat is not persisted in database


## Customer (Ecommerce) admin chat
Soaggy chat must be able to permit customers to chat to another user know as 'product owner'

1. Chat is related to the PRODUCT AND ITS SELLER
2. Sellers manages their chats
3. An icon on a product can be cliked(by the user) and opens a chat on the right with the product owner or application administror.
4. If user is connected, chat is persistent.
5. if user is not connected, chat is not persistent


# MOBILE CHAT
See wechat/viber application for example

1. Can chat with contacts in mobile phone
2. Need the phone number/or not!!!
3. Group chat
4. EMOTICONS: CREATE MALAGASY CONTEXTUAL EMOTICONS
6. VOICE: NEXT VERSION
8. VIDEO: NEXT VERSION
9. SECURITY: SSL/EPHEMERAL(PAYANT)





