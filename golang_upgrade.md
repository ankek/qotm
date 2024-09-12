go version
go vet ./... && go mod tidy && go fix ./... && go test ./... && go mod tidy


# go get -u golang.org/x/tools/...

go get -u github.com/gorilla/websocket
go get -u google.golang.org/grpc

go get google.golang.org/grpc@v1.56.3
