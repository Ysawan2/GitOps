FROM alpine
WORKDIR /app

RUN echo "Hello World from docker" > /app/index.html
#COPY ./index.html /app/index.html

# Just adding some comment
ENTRYPOINT [ "python3", "-m", "http.server", "&" ]



