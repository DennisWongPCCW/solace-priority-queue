# Solace-Spring-Service

[POST] to send a queue
http://localhost:8000/demo/sendQueue

{
    "type": "Queue",
    "path": "OtherQueue",
    "payload": "testing12345678912345678"
}

[POST] to send a topic
http://localhost:8000/demo/sendTopic

{
    "type": "Topic",
    "path": "demo/first/test",
    "payload": "testing12345678912345678"
}
#   S o l a c e _ P O C _ F i n a l  
 