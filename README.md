# proj-microservices-educorp
Projeto completo do curso de microservices da Educorp


Construir imagens e subir containers:

`$ docker-compose up - d --build`


Recuperar info do Actuator do gateway, único serviço exposto:

`$ curl -i http://localhost:8080/e-restaurante/actuator/info`