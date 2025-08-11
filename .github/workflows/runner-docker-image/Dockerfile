FROM        docker.io/redhat/ubi9
RUN         dnf install libicu -y
RUN         useradd github
USER        github
WORKDIR     /home/github
RUN         curl -o actions-runner-linux-x64-2.327.1.tar.gz -L https://github.com/actions/runner/releases/download/v2.327.1/actions-runner-linux-x64-2.327.1.tar.gz && tar xzf ./actions-runner-linux-x64-2.327.1.tar.gz
