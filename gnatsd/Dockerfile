# based on lcacciagioni/dockerfiles
FROM google/golang
WORKDIR /gopath/src/gnatsd
RUN ["go", "get", "github.com/apcera/gnatsd"]
EXPOSE 4222 4223 4224
ENTRYPOINT ["/gopath/bin/gnatsd"]
