spring-websocket-chat

[![Git](https://app.soluble.cloud/api/v1/public/badges/db53bf84-deec-468d-a7eb-bfaaec595e31.svg?orgId=521549019486)](https://app.soluble.cloud/repos/details/github.com/brianbyers/spring-websocket-chat?orgId=521549019486)  
=====================

[![Join the chat at https://gitter.im/salmar/spring-websocket-chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/salmar/spring-websocket-chat?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Chat application using AngularJS and Spring WebSockets (STOMP over WebSockets)


![Spring WebSocket Chat](http://www.sergialmar.com/wp-content/uploads/2014/09/spring-websocket-chat-room.png "Spring WebSocket Chat")
## Features
- Built with Spring Boot
- User login
- Chat message broadcasting and private messages (filtering profanities)
- Presence tracking sending notifications when users join / leave
- Broadcast notifications when users are typing
- WebSockets stats exposed at /stats
- WebSocket security with Spring Security
- Spring Session integration

## Running the app
gradle bootRun
