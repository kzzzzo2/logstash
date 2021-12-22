FROM golang:1
RUN go env -w GO111MODULE=off && go get gopkg.in/yaml.v2
WORKDIR /usr/local/src/env2yaml
CMD ["go", "build"]
