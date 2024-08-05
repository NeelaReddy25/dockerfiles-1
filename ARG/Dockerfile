ARG version
FROM almalinux:${version:-8}
RUN cat /etc/*release
ARG COURSE=Docker
ARG TRAINER=Neelareddy
ARG DURATION=120HRS
RUN echo "course is: ${COURSE}, trainer is: ${TRAINER}, duration is: ${DURATION}"
CMD ["sleep", "100"]