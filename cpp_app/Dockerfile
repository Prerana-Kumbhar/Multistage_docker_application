FROM ubuntu:latest

RUN apt update && apt install -y g++

WORKDIR /app

COPY app.cpp .

RUN g++ app.cpp -o hello

CMD ["./hello"]


