ARG version
FROM almalinux:${version:-9}
#ARG course="DevOps with AWS" \
# ENV course="DevOps with AWS" \
#     duraton="120hrs" \
#     trainer="shivakumar"
ARG course="DevOps with AWS" \
duration="120hrs" 
ENV duration=$duration
RUN echo "Course: $course, duration: $duration"
CMD ["sleep","100"]