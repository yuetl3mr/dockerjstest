#!/usr/bin/env groovy

pipeline {
    agent any

    tools {
        dockerTool 'docker'
    }

    stages {
        stage('Build') {
            steps {
                sh 'docker --version'
                sh 'docker build -t yuetl/test:0.1.0 .'
            }
        }
    }
}

