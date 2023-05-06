FROM golang:alpine AS builder

LABEL author="Rogerio dos Santos Silva<roger7331@gmail.com>" \
    version="1.0" \
    description="Desafio docker fullycle" 

WORKDIR /app
COPY ./*.go ./
RUN go mod init github.com/rogeriostos/fullcicle
RUN go build -gccgoflags "-s -w" -o /fullcicle

FROM scratch
WORKDIR /
COPY --from=builder /fullcicle /fullcicle

ENTRYPOINT [ "/fullcicle" ]