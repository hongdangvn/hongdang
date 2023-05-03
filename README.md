Tool: Postman

Request method: POST

URL: https://sampleproject.ingest.mpdev.io/v1/track

Tab Body: 
- Select Raw
- Drop-down: JSON instead Text

1. Case: User add to cart successfully
 Copy/paste below text to the box:
 {
  "organizationId": "O01",
 
   "projectId": "P01",
  
   "anonymousId": "A01",
  
   "userId": "U01",
  
   "requestId": "R01",
  
   "category": "C01",
  
   "event": "E01",
  
   "context": {
  
     "userAgent": "UA01",
    
     "deviceType": "pc"
    
   },
  
   "properties": {["new", "red"]},
  
   "sentAt": "2023/04/30"
  
 }

 Click Send button

 Response code:
 - 200: { "result": "ok" }

2. Case: User add to cart successfully
 Copy/paste below text to the box:
 {
  "organizationId",
 
   "projectId": "P02",
  
   "anonymousId": "A02",
  
   "userId": "U02",
  
   "requestId": "R02",
  
   "category": "C02",
  
   "event": "E02",
  
   "context": {
  
     "userAgent": "UA02",
    
     "deviceType": "laptop"
    
   },
  
   "properties": {["new", "red"]},
  
   "sentAt": "2023/04/30"
  
 }

 Click Send button

 Response code:
 - 400: Bad request

