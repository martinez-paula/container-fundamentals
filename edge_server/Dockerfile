FROM alpine:3.19.1
LABEL org.opencontainers.image.authors="Paula Martinez"
LABEL org.opencontainers.image.source=https://github.com/jduncan-rva/container-fundamentals
LABEL org.opencontainers.image.description="Containter Fundamentals - Static Website Image"
LABEL org.opencontainers.image.licenses=APACHE2
LABEL server_type=edge_server
RUN apk update && apk add --no-cache nginx   
COPY to_copy ./
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
