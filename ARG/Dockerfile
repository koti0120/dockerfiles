ARG version
FROM almalinux:${version:-9}
#here :-9 means we give to take default if any version not give then take 9
ARG author="venkata koti" \
    tool="docker" \
    description="this is docker practice"
RUN echo "Name:$author,Tool:$tool,Description:$description"
CMD ["sleep","120"]