FROM golang:1.22-bullseye
RUN  go install github.com/bufbuild/buf/cmd/buf@latest && go install github.com/fullstorydev/grpcurl/cmd/grpcurl@latest && go install google.golang.org/protobuf/cmd/protoc-gen-go@latest && go install connectrpc.com/connect/cmd/protoc-gen-connect-go@latest

RUN go install github.com/cweill/gotests/gotests@latest && go install github.com/josharian/impl@latest && go install github.com/go-delve/delve/cmd/dlv@latest
RUN go install honnef.co/go/tools/cmd/staticcheck@latest
RUN go install golang.org/x/tools/gopls@latest
RUN go install github.com/air-verse/air@latest
RUN go install github.com/envoyproxy/protoc-gen-validate@latest