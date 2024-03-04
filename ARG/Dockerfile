ARG version
FROM almalinux:${version:-8}
# the above version ARG cannot be used anyware below
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
RUN echo "COURSE:${COURSE} , TRAINER:${TRAINER}"
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
CMD ["sleep","100"]