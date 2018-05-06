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
 {
   Name: "Todo 1",
   Disc: "todo One",
   Completed: false,
   Due: "12/12/2018"
 }

Update Book
PUT todos/{id}

 Request sample
 {
   Name: "Todo 1",
   Disc: "todo One",
   Completed: false,
   Due: "12/12/2018"
 }
