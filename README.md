Method: POST
Tab Body: 
- Select Raw
- Drop-down: JSON instead Text

Copy/paste below text to the box:
{
 "organizationId": "string",
  "projectId": "string",
  "anonymousId": "string",
  "userId": "string",
  "requestId": "string",
  "category": "string",
  "event": "string",
  "context": {
    "userAgent": "string",
    "deviceType": "pc"
  },
  "properties": {},
  "sentAt": "string"
}
Click Send button
Response code:
- 200: { "result": "ok" }
- no data
- 400 { "message": "Invalid request body" }
