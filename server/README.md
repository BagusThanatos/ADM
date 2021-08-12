# Server
Server side code. Written in Go
Linux only. There's literally no reason to write for Windows

We should always validate everything here

## Current Requirements
- PostgreSQL
If we do use Passwords, the should hashed using SHA3-512 with salt

### Required environment variables
```
POSTGRES_HOST
POSTGRES_USER
POSTGRES_PASSWORD
POSTGRES_DB
```

## Currrent proposed libraries:
1. For HTTP Server:
- github.com/julienschmidt/httprouter

2. For logging
- go.uber.org/zap

3. Will need something to copy result to remote host
