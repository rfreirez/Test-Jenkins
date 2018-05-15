#!/usr/bin/env groovy

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh '/var/jenkins_home/tools/hudson.tasks.Maven_MavenInstallation/m3/bin/mvn clean install'
            }
        }
    }
}
