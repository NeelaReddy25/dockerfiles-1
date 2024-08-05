ARG version
FROM almalinux:${version}
RUN cat /etc/*release
ARG COURSE
ARG TRAINER
ARG DURATION
RUN echo "course is: ${COURSE}, trainer is: ${TRAINER}, duration is: ${DURATION}"
CMD ["sleep", "100"]