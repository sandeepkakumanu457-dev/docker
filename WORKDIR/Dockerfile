FROM almalinux:9
RUN mkdir /tmp/work-dir-demo
WORKDIR /tmp/work-dir-demo
RUN pwd
RUN echo "hello hi every one" > hello.txt
CMD ["sleep", "100"] #this command can be override by passing a different command when running the container, it will always sleep for 1000 seconds.