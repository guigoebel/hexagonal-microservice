# hexagonal-microservice

Studying Hexagonal Microservice Architecture
Building URL-Shorter to 9 chars

https://www.google.com -> 98sj1-293
http://localhost:8000/98sj1-293 -> https://www.google.com

Service will connect to repository via Port and also have a serializer adapter that connect to a http transport server
repo <- service -> serializer -> http
