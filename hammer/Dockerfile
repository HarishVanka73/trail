FROM nginx
RUN apt update
RUN apt install python3 -y

WORKDIR Users/User/pythonstuff

COPY hello.py ./

EXPOSE 8080

CMD ["echo","hello world"]


