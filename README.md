# Todo-REST-API-in-Golang
A simple todo REST API created in golang

Simple RESTful API to create, read, update and delete todos. No database implementation yet

Quick Start

# Install mux router
go get -u github.com/gorilla/mux
go build
./go_restapi

Endpoints

Get All Todos
GET todos

Get Single Todo
GET todos/{id}

Delete Todo
DELETE todos/{id}

Create Todo
POST todos

 Request sample
# {
##   "name": "Todo 2",
##   "discription": "todo Two",
##   "completed": true,
##   "due": "02/06/2018"
# }

Update Book
PUT todos/{id}

 Request sample
 #{
 ##  "name": "Todo 2",
 ##  "discription": "todo Two",
 ##  "completed": true,
 ##  "due": "02/06/2018"
 #}
