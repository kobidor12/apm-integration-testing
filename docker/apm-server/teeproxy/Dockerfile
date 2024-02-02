FROM golang:1.22rc2-bookworm
ENV CGO_ENABLED=0
# use fork to quickly pin https://github.com/chrislusf/teeproxy
RUN go install github.com/graphaelli/teeproxy@latest
CMD ["teeproxy"]
