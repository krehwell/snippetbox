# Snippetbox 📦

Fullstack web app created using Golang that allows users to create snippets and share it. 
It's monolithic, eww. But, hey! I learned a lot. 

<details>
    <summary>Home page</summary>
    <img src="https://i.imgur.com/ra6xFkR.png"/>
</details>

<details>
    <summary>Snippet page</summary>
    <img src="https://i.imgur.com/BDgcdbV.png"/>
</details>

<details>
    <summary>Account page</summary>
    <img src="https://i.imgur.com/9JZKt4P.png"/>
</details>

## Stack Used 📚
- [mysql](https://github.com/go-sql-driver/mysql)
- [mysqlstore](https://github.com/alexedwards/scs/mysqlstore) - session manager
- [httprouter](https://github.com/julienschmidt/httprouter)
- [alice](https://github.com/go-sql-driver/mysql) - middleware handler
- etc.

## Run Locally
```bash
# run on browser https://localhost:4000/
go run ./cmd/web

# run testing
go test -v ./...
```

## Pages 📃
- /home
- /about
- /user/login
- /user/signup
- /snippet/view/:id
- /snippet/create
- /account/view
- /account/password/update

## Covered/Learned/Implemented Things 🌈🦄
- manage http router, handler, middleware in go
- go configuration/ project setup convention
- dynamic html template
- processing form in go
- stateful http
- decoupling project from db
- security improvement: https, csrf protection, connection timeout
- context
- go embedded files
- go generics
- testing includes: 
    - unit testing and sub-tests, 
    - end-to-end testing, 
    - mocking dependencies,
    - integration testing,
    - profiling test coverage
