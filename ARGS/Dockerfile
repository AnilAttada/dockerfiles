ARG version
FROM almalinux:${version:-9}
ENV COURSE="DevOps" \
    DURATION="120" \
    LISTENER="${LISTENER}"
ARG LISTENER="Anil"
RUN echo "Hi, course is ${COURSE}, duration is ${DURATION}, listener is ${LISTENER}"
CMD ["sleep", "1000"]

