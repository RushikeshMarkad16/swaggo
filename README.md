# swaggo

#### Swaggo autogenerates the api documentation from annotations from code


### Installation : 
go install github.com/swaggo/swag/cmd/swag@latest </br>

go get -u github.com/swaggo/swag/cmd/swag </br>
go get -u github.com/swaggo/http-swagger </br>
go get -u github.com/alecthomas/template </br>

### Generate docs:
swag init : generates go,yaml,json files </br>
Swag init -g <filename> : if annotations are not in main </br>
swag init --outputTypes go,yaml : to generate specific files (here only go and yaml files will be generated) </br>


Run the server and you can see docs at http://localhost:8080/swagger/index.html#/ (change port no accordingly) </br>
OR </br>
Copy paste the contents of generated docs/swagger.json file in https://editor.swagger.io/ 


### Documentation:
You can explore more about swaggo at https://github.com/swaggo/swag 

- Basic Swagger structure : https://swagger.io/docs/specification/2-0/basic-structure/ 
