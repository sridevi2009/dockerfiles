FROM almalinux:8
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
RUN echo "Course: ${COURSE}, Trainer: ${TRAINER}"
ENV COURSE=${COURSE}
ENV TRAINER=${TAINER}
CMD ["sleep","100"]