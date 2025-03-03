ARG version
FROM almalinux:${version:-9}
ENV course="DevSecOps With Cloud" \
    trainer="Shiva Kumar Reddy" \
    duration="120Hrs"
ARG USERNAME=Sivakumar
RUN echo "Hello User: ${USERNAME}, Image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]