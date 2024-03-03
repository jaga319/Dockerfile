FROM almalinux:8
RUN yum install nginx -y
ENV TRAINING="DEVOPS" \
      TRAINER="SIVE"    \
      DURATION="120HRS"
CMD ["nginx", "-g", "daemon off;"]