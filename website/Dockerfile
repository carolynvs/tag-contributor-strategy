FROM klakegg/hugo:0.79.0-ext-alpine

WORKDIR /src/website
COPY website/go.* /src/website/
RUN go mod download

COPY . /src/
