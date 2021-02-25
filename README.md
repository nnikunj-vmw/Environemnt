# Environment
Sample project to change env values using actuator end points


Get Default Value

curl http://localhost:8080/actuator/env/foo

Set new Val

curl -H "Content-Type: application/json" -X POST --data '{"name":"foo", "value":"kar"}' http://localhost:8080/actuator/env 

Refresh 
curl -X POST http://localhost:8080/actuator/refresh
