# working-with-concurrency-in-go

# About the project
- Build a simple web using concurrency in Go to send mail, generate PDF, with function login, logout, register, validate mail, validate token.

# Built With
- Docker (build container redis,postgres,mailhog)
- Golang (goquery,go-alone,pgconn,gofpdf,go-premailer...)
- Redis (store session)
- Postgres (database)

# Prerequisites
- Install Go
- Install Docker
- Install Make

# Install 
- git clone https://github.com/vinhhung263/working-with-concurrency-in-go.git
- RUN docker-compose up -d
- RUN make start
- Test by : 
    go test -v . 
- Test coverage : 
    go test -coverprofile=coverage.out
    
    go tool cover -html=coverage.out
   
# Usage
- Open browser and go to localhost:81
