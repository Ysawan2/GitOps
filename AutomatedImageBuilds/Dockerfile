FROM alpine
WORKDIR /app

RUN echo "Hello World from docker" > /app/index.html
#COPY ./index.html /app/index.html

# adding a comment
ENTRYPOINT [ "python3", "-m", "http.server", "&" ]



