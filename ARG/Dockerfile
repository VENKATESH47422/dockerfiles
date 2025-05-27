FROM almalinux:8
ARG username
RUN adduser $username
USER $username 
ARG COURSE
ARG LISTENER
ENV COURSE=${COURSE}
ENV LISTENER=${LISTENER}
CMD ["sleep", "100"]