#!groovy
pipeline {
  stage('Docker Build') {
    agent any
      
      steps {
      	sh 'docker build -t shanem/spring-petclinic:latest .'
      }
    }
  }

