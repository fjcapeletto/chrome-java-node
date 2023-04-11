# chrome-java-node
Chrome + Node 19 + Java 11 JRE Docker Image

This image is built on the latest `node:19-buster` image and installs Java 11 JRE (OpenJDK) and last google-chrome-stable as well.

Pull requests & suggestions are welcome.

In case of any problems with this image please report on Github.

I made this image to setup my SonarQubr QA Jenkins pipeline (using docker agents) for my NodeJS projects:

* Headless Chrome is need for run unit tests using Karma framework in NodeJS projects.
* JRE is needed to run Sonar-scanner analysis


The pre built image can be downloaded using Docker.

    docker pull fjcapeletto/chrome-java-node

