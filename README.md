# Environment
Sample project for writable properties

curl http://localhost:8080/actuator/env/foo
curl -H "Content-Type: application/json" -X POST --data '{"name":"foo", "value":"kar"}' http://localhost:8080/actuator/env 

curl -X POST http://localhost:8080/actuator/refresh
