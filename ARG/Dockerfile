ARG version
FROM almalinux:${version:-8}
RUN cat /etc/*release
ARG COURSE
ARG TRAINER
ARG DURATION
RUN echo "course is: ${COURSE}, trainer is: ${TRAINER}, duration is: ${DURATION}"
CMD ["sleep", "100"]