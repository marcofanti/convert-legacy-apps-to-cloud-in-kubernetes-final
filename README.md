# Converting Legacy Applications to Cloud Native in Kubernetes


http POST 192.168.99.125:30055/profile username=unamerkel password=changeme    firstName=Una lastName=Merkel email=unamerkel@example.com
HTTP/1.1 200
Connection: keep-alive
Content-Type: application/json
Date: Sun, 07 Jun 2020 20:37:56 GMT
Keep-Alive: timeout=60
Transfer-Encoding: chunked

{
    "email": "unamerkel@example.com",
    "firstName": "Una",
    "id": 1,
    "imageFileContentType": null,
    "imageFileName": null,
    "lastName": "Merkel",
    "password": "changeme",
    "username": "unamerkel"
}

http 192.168.99.125:30055/profile/unamerkel
HTTP/1.1 200
Connection: keep-alive
Content-Type: application/json
Date: Sun, 07 Jun 2020 20:38:01 GMT
Keep-Alive: timeout=60
Transfer-Encoding: chunked

{
    "email": "unamerkel@example.com",
    "firstName": "Una",
    "id": 1,
    "imageFileContentType": null,
    "imageFileName": null,
    "lastName": "Merkel",
    "password": "changeme",
    "username": "unamerkel"
}