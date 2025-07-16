ARG version
FROM almalinux:${version:-9}
ENV course="devops" \
    duration="120hrs" 
ARG student="harsha"
ENV student=$student
RUN echo "hi, course is: ${course}, duration is: ${duration}, student is: ${student}"
CMD ["sleep", "1000"]