      ____                   _   _                 __          __  _                    _        _      _____ _           _
     / __ \                 | | (_)                \ \        / / | |                  | |      | |    / ____| |         | |
    | |  | |_   _  ___ _ __ | |_ _ _ __    ______   \ \  /\  / /__| |__  ___  ___   ___| | _____| |_  | |    | |__   __ _| |_
    | |  | | | | |/ _ \ '_ \| __| | '_ \  |______|   \ \/  \/ / _ \ '_ \/ __|/ _ \ / __| |/ / _ \ __| | |    | '_ \ / _` | __|
    | |__| | |_| |  __/ | | | |_| | | | |             \  /\  /  __/ |_) \__ \ (_) | (__|   <  __/ |_  | |____| | | | (_| | |_
     \___\_\\__,_|\___|_| |_|\__|_|_| |_|              \/  \/ \___|_.__/|___/\___/ \___|_|\_\___|\__|  \_____|_| |_|\__,_|\__|

Chat application using AngularJS and Spring WebSockets (STOMP over WebSockets)

## Features
- Spring Boot
- User login
- Presence tracking sending notifications when users join / leave
- WebSocket security with Spring Security
- Spring Session integration

## Running the app
gradle bootRun

## Coming up
- Logging
- Data storage clustering for chat transcripts
- Perf testing scripts
- Travis ci
- Broadcast notifications when users are typing
- WebSockets stats exposed at /stats
- Queues for chats
- heroku/aws (?)
