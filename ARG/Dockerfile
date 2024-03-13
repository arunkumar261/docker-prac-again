# FROM almalinux:8
# ARG username
# RUN adduser $username
# USER $username
# CMD [ "sleep", "100" ]

# FROM almalinux:8
# ARG username
# RUN adduser $username
# USER $username
# ARG COURSE
# ARG TRAINER
# RUN echo "course is :${COURSE} and Trainer is : ${TRAINER}"
# ENV COURSE=${COURSE}
# ENV TRAINER=${TRAINER}
# CMD [ "sleep", "100" ]

ARG version
FROM almalinux:${version}
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
RUN echo "course is :${COURSE} and Trainer is : ${TRAINER}"
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
CMD [ "sleep", "100" ]