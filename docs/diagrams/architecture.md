## Product choice

Product name: Telegram;
Link to the product's website: <https://web.telegram.org>;
Telegram is a world-known messanger. The founder of Telegram is Pavel Durov.

## Main components

![Telegram Component Diagram](/docs/diagrams/out/telegram/component-diagram/Component%20Diagram.svg);
Link: <https://github.com/inno-se-toolkit/lab-01-market-product-and-git/blob/main/docs/diagrams/src/telegram/component-diagram.puml>;

[Media & File Service] - A component responsible for traficking and saving media between users.
[Bot API Server] - A component responsible for Bot API.
[Auth & Session Service] - Auth component.
[Mobile App (iOS/Android)] - mobile app component.
[Desktop App] - desktop app component.

## Data flow

![Telegram Sequence Diagram](/docs/diagrams/out/telegram/sequence-diagram/Sequence%20Diagram.svg);
Link: <https://github.com/inno-se-toolkit/lab-01-market-product-and-git/blob/main/docs/diagrams/src/telegram/sequence-diagram.puml>.

box "Core Services": some core services function here, participants:
-participant "Auth Service" as AuthSvc;
-participant "Media Service" as MediaSvc;
-participant "Message Service" as MsgSvc;
-participant "Push Service" as PushSvc.

## Deployment

![Telegram Deployment Diagram](/docs/diagrams/out/telegram/deployment-diagram/Deployment%20Diagram.svg);
Link: <https://github.com/inno-se-toolkit/lab-01-market-product-and-git/blob/main/docs/diagrams/src/telegram/deployment-diagram.puml>.

I cannot open the picture but something importanta happens there...

## Assumptions

I assume the cloud storage system implements deduplication to optimize storage costs for shared media files.

## Open questions

How does the data flow look like in secret chats? Who made Telegram?
