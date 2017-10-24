#!groovy

@Library('MicroserviceBuilder') _
microserviceBuilderPipeline {
  image = 'demoxxx'
  test = 'false'
  deploy = 'true'
  mavenImage = 'mycluster:8500/default/mvn:custom'
  mvnCommands = '-s /usr/share/maven/ref/settings-docker.xml clean package'
}
