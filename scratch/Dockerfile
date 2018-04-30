# build stage
FROM golang:alpine AS build-env
RUN apk add --no-cache git
RUN CGO_ENABLED=0 go get github.com/github/git-sizer

FROM scratch
COPY --from=build-env /go/bin/git-sizer /usr/bin/git-sizer
ENTRYPOINT ["git-sizer"]
