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

# Rest API Design Patterns

<img width="448" height="236" alt="image" src="https://github.com/user-attachments/assets/f7a328c2-e1dd-4737-979f-9b75090dd80b" />

<img width="434" height="257" alt="image" src="https://github.com/user-attachments/assets/bf31adaf-7fb9-40f8-a4fd-eba9c7e157aa" />

<img width="855" height="504" alt="image" src="https://github.com/user-attachments/assets/03af00bc-4880-4d2d-91b6-851ba2a9cd4f" />

<img width="795" height="434" alt="image" src="https://github.com/user-attachments/assets/d3792d81-966e-4e2b-b563-4342157e7753" />

<img width="435" height="227" alt="image" src="https://github.com/user-attachments/assets/3e915b36-95b2-4e38-91b4-a09aad89ab18" />

<img width="401" height="263" alt="image" src="https://github.com/user-attachments/assets/a6d062b5-52c4-44cb-828d-70b95a0a6bf5" />

<img width="878" height="462" alt="image" src="https://github.com/user-attachments/assets/4a8cf722-35ac-4c92-8766-64a60ec9542b" />

# GraphQL Design

<img width="437" height="250" alt="image" src="https://github.com/user-attachments/assets/ca9e4091-61c5-4c73-ac99-c68710003398" />

GraphQL design pattern was created because developer ars not getting the results that are expected even after several RestAPI calls and the latency increases

<img width="459" height="260" alt="image" src="https://github.com/user-attachments/assets/200e45fb-49fc-4c7e-9fc0-534f898d39d1" />

<img width="793" height="492" alt="image" src="https://github.com/user-attachments/assets/c7b86003-261c-4d1c-b114-345db4f949c6" />

<img width="403" height="250" alt="image" src="https://github.com/user-attachments/assets/40d6f356-d8fe-453c-97c0-0ebb57afab6f" />

<img width="410" height="221" alt="image" src="https://github.com/user-attachments/assets/4e51859e-c8a4-47c9-9631-58844c632d5b" />

<img width="420" height="257" alt="image" src="https://github.com/user-attachments/assets/30b762a8-9d60-496b-aee8-af8233491460" />

Error handling in GraphQL was bit different because garaphql will return 200 status every time even with error. we explicity mention the error in body.

<img width="295" height="198" alt="image" src="https://github.com/user-attachments/assets/c7c6eb00-82fd-4657-984c-776a4bac30c3" />

# Authentication

<img width="803" height="425" alt="image" src="https://github.com/user-attachments/assets/a9a773b5-9dde-498b-86e9-22843365348c" />

<img width="338" height="242" alt="image" src="https://github.com/user-attachments/assets/8e267045-acea-4a3c-9dd8-e5a5288fda33" />

<img width="391" height="245" alt="image" src="https://github.com/user-attachments/assets/c9194ab9-f34a-4b00-9e0f-7c17b588d7ee" />

<img width="420" height="262" alt="image" src="https://github.com/user-attachments/assets/8528af3f-dad9-415f-a9d1-2c2e54a9dc65" />

<img width="428" height="263" alt="image" src="https://github.com/user-attachments/assets/88a8b886-8eb0-4860-b2db-55a74d00a51a" />

<img width="424" height="258" alt="image" src="https://github.com/user-attachments/assets/a3328c71-a56c-4a1f-a8ff-57b1562f32f2" />

# Authorization

<img width="440" height="244" alt="image" src="https://github.com/user-attachments/assets/04de2d23-dcf5-4daf-963f-9f22058255fd" />

<img width="795" height="480" alt="image" src="https://github.com/user-attachments/assets/9be6091e-816e-474f-90d6-3258fff26e06" />

<img width="627" height="461" alt="image" src="https://github.com/user-attachments/assets/6884fa2b-6262-48b0-805a-2018e0190d16" />

<img width="261" height="226" alt="image" src="https://github.com/user-attachments/assets/8b45e8fe-b572-4679-ba4e-7b4c367bacdd" />

<img width="399" height="242" alt="image" src="https://github.com/user-attachments/assets/d4e743b2-0387-4f89-a132-df5af6b74736" />

<img width="640" height="468" alt="image" src="https://github.com/user-attachments/assets/fd3db0c7-631c-4823-a886-91cf1e81ecac" />

<img width="316" height="219" alt="image" src="https://github.com/user-attachments/assets/07a5b6ab-5013-43b0-94b9-1b58bf560434" />

<img width="278" height="250" alt="image" src="https://github.com/user-attachments/assets/577eb432-420b-43cc-8916-fab6760f3589" />

<img width="269" height="232" alt="image" src="https://github.com/user-attachments/assets/33e8640e-eaf2-4c5a-a367-719ff0e8b94e" />

# Security

<img width="355" height="232" alt="image" src="https://github.com/user-attachments/assets/5b566128-5bdc-465c-abe8-fec91493c67e" />

<img width="380" height="227" alt="image" src="https://github.com/user-attachments/assets/b1ca8325-a5f9-4c6d-973a-2724f38944ce" />

<img width="383" height="248" alt="image" src="https://github.com/user-attachments/assets/d89f72e1-b2fd-4d79-89f9-c7ece9079f6a" />

<img width="415" height="210" alt="image" src="https://github.com/user-attachments/assets/a8441d37-f6a8-4c71-bb57-c64c7a320fd4" />

<img width="404" height="230" alt="image" src="https://github.com/user-attachments/assets/73ac0414-4733-42da-8c45-0bd95a8ec649" />

<img width="380" height="245" alt="image" src="https://github.com/user-attachments/assets/39604672-e371-4a4d-9a14-054628088c99" />

<img width="883" height="493" alt="image" src="https://github.com/user-attachments/assets/33165e1e-df6c-4f3d-bf63-8e74df7bae35" />


