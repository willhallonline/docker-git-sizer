# build stage
FROM golang:alpine AS build-env
RUN apk add --no-cache git
RUN go get github.com/github/git-sizer

FROM debian:stretch-slim
COPY --from=build-env /go/bin/git-sizer /usr/bin/git-sizer
CMD ["git-sizer"]
