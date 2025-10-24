<img width="723" height="474" alt="image" src="https://github.com/user-attachments/assets/58dcd7a2-35a4-42b1-83ea-0c073a240502" />

## Different Types of API
<img width="398" height="263" alt="image" src="https://github.com/user-attachments/assets/2eb98122-b33c-4de8-99f6-5f799b6be373" />
<img width="422" height="257" alt="image" src="https://github.com/user-attachments/assets/49190ab1-d8de-4268-8b7f-15577dc36147" />

Design Principles

<img width="278" height="245" alt="image" src="https://github.com/user-attachments/assets/128c69d1-8684-41ec-9358-d3f368810267" />
<img width="413" height="257" alt="image" src="https://github.com/user-attachments/assets/1619599a-1d5a-4d6f-bcec-1635f6dc6fa4" />

HTTP, Status Codes are used in RESTful API, CRUD Operationdesign

HTTP, Status Codes are used in GraphQL API design

Websockets are used in Real-time APIs

<img width="388" height="256" alt="image" src="https://github.com/user-attachments/assets/7124d6e7-2a35-4167-8806-a2966027130c" />

when are building APIs we are more concerned with Application layer. this where the communication starts between client and server

# HTTP/HTTPS Protocal
<img width="368" height="251" alt="image" src="https://github.com/user-attachments/assets/deadee58-00b4-4270-8058-e191e3898312" />
<img width="341" height="216" alt="image" src="https://github.com/user-attachments/assets/8df9ffec-d8ed-4b0b-a7d1-6c7f033c705b" />

In HTTP/HTTPS communication happens when the client send the request to server and the server gives response. for each update in either side of cilent or server request need to be send then only response get generated.
# websockets
<img width="379" height="266" alt="image" src="https://github.com/user-attachments/assets/d88449ff-f118-48bb-be63-8d7a3d098d34" />

websockets are used in real-time API building when there is frequent updates in the server that need to be transmitted to client. It works with UDP once the hand-shake is done continous commnincation will take place.
# AMQP
<img width="366" height="261" alt="image" src="https://github.com/user-attachments/assets/7416d78b-0b8c-474c-8bdf-fd93f226b3cc" />

In AMQP Producer is to send the message to consumer before it reaches consumer it is stored in meesage Queu whenever consumer is free it will take the messages that are in queue and work on it eg: it's like app use to send notifications of content continously whenever the user is free he will consume the content.

# gRPC- google remote procedure call

<img width="349" height="254" alt="image" src="https://github.com/user-attachments/assets/6885d544-7f65-4ae7-b169-337a33b7cc9d" />

<img width="380" height="233" alt="image" src="https://github.com/user-attachments/assets/77ef13a8-a8d7-4e68-9d26-3e880a6c2954" />

## Transport Layer
<img width="413" height="251" alt="image" src="https://github.com/user-attachments/assets/5508cf5d-2665-4818-8edf-8d309aa00b06" />
<img width="401" height="263" alt="image" src="https://github.com/user-attachments/assets/2d713ba3-e704-4f2b-87fb-6c5079991570" />

In TCP there is guarantee that all packets sent by cilent will reach the server in the same order that was sent by client

In UDP there is no guarentee that all packets sent by cilent will reach the server there is chance of missing.
