FROM almalinux:8
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
RUN echo "COURSE:${COURSE} , TRAINER:${TRAINER}"
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
CMD ["sleep","100"]