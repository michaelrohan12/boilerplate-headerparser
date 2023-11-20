# Request Header Parser Microservice

This is the boilerplate for the Request Header Parser Microservice project.

- A request to /api/whoami should return a JSON object with your IP address in the ipaddress key.
- A request to /api/whoami should return a JSON object with your preferred language in the language key.
- A request to /api/whoami should return a JSON object with your software in the software key.

## API Reference

#### Get header info (ipaddress, lanaguage and software)

```http
  GET /api/whoami
```

| Parameter | Type | Description                                                            |
| :-------- | :--- | :--------------------------------------------------------------------- |
| -         | -    | Returns the ip address, lanaguage and software from the request header |
