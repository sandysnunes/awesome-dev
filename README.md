# awesome-dev

# Developer

1. Developer Roadmap <https://github.com/kamranahmedse/developer-roadmap>

# Tools

1.

### JSON

1.
2.

# Markdown

- Tutotial: <https://agea.github.io/tutorial.md/>

# Java Script

1. Javascript Algorithms <https://github.com/trekhleb/javascript-algorithms>

### React

1. Create React App <https://github.com/facebook/create-react-app>


`npx create-react-app my-app`<br>
`cd my-app`<br>
`yarn start`<br><br>

`yarn add axios`<br>
`yarn add react-router-dom`


2. React Developer Tools - https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi



# Go

### Frameworks and Libs

1. Wire - Dependency Injection <https://github.com/google/wire>
2. Gin Gonic - Web framework <https://gin-gonic.com/>
3. Excelize - Read and Write XLSX files <https://github.com/360EntSecGroup-Skylar/excelize>


### Interesting Go Repositories

1. Awesome Go <https://github.com/avelino/awesome-go>
2. Ultimate go <https://github.com/hoanhan101/ultimate-go>
3. The Go Programming Language <https://github.com/adonovan/gopl.io>
4. Go Clean Architecture <https://github.com/bxcodec/go-clean-arch>
5. Project Layout <https://github.com/golang-standards/project-layout>
6. Go Patterns <https://github.com/tmrts/go-patterns>
7. Popular Repositories <https://github.com/kaxap/arl/blob/master/README-Go.md>

# APIs

1. Public APIs <https://github.com/public-apis/public-apis>



# Docker images

### Redis
- `docker run --name redis-local -p 6379:6379 -d redis`
- `sudo apt install redis-tools #redis-cli`


### Mongo

- `docker run --name mongo-local -v /opt/mongo:/data/db -p 27017:27017 -p 28017:28017 -e MONGO_INITDB_ROOT_USERNAME=username -e MONGO_INITDB_ROOT_PASSWORD=password  -d mongo`

### PostgreSQL

- `docker run --name pg-local -p 5432:5432 -v /opt/db-backup:/opt/db-backup -v /opt/local-db-data:/var/lib/postgresql/data -e POSTGRES_PASSWORD=postgres -d postgres:12.2`

### FTP

- `docker run -d -v /opt/ftp-local:/home/vsftpd -p 20:20 -p 21:21 -p 47400-47470:47400-47470 -e FTP_USER=user -e FTP_PASS=password -e PASV_ADDRESS=172.17.0.1 --name ftp  bogem/ftp`



# Books

- Refactoring: Improving the Design of Existing Code - Martin Fowler
- Code Complete - Steve McConnell
- The Mythical Man-Month - Frederick Brooks
- Enterprise Integration Patterns - Gregor Hohpe
- Patterns of Enterprise Application Architecture - Martin Fowler
- Design Patterns: Elements of Reusable Object-Oriented Software - Eric Gamma


# Design Patterns

1.  https://github.com/DovAmir/awesome-design-patterns

# Command Line

1. The Art of Command Line
 <https://github.com/jlevy/the-art-of-command-line>
 

 # cheat sheets