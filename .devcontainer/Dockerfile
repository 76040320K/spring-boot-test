ARG VARIANT=11
FROM mcr.microsoft.com/vscode/devcontainers/java:${VARIANT}
ARG GRADLE_VERSION="7.4"
RUN su vscode -c "source /usr/local/sdkman/bin/sdkman-init.sh && sdk install gradle \"${GRADLE_VERSION}\""
