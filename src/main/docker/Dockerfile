FROM java:8-jre
MAINTAINER Mradul Pandey <pandeymradul@gmail.com>

LABEL VERSION="@project.version@"
LABEL DESCRIPTION="@project.description@"
LABEL GIT_COMMIT_ID="@git.commit.id@"

ADD ./@project.build.finalName@.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/@project.build.finalName@.jar"]

EXPOSE 8080