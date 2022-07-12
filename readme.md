Inspired by https://github.com/dduportal/jenkins-examples

Starts a latest LTS Jenkins. 

Todo: remove yeager

`run --rm -v "$(pwd):$(pwd):ro" --entrypoint=jenkins-plugin-cli jenkins/jenkins:lts-jdk11 --available-updates --war /usr/share/jenkins/jenkins.war --output txt --plugin-file "$(pwd)"/plugins.txt > 1.tmp`