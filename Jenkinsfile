pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/nikhil5976/Devopswebapplication.git', branch: 'master', credentialsId: 'raju', poll: true)
      }
    }
    
     stage('Build') {
       steps {
           echo 'Building my maven web project'
           bat 'mvn clean package'
          }
        }
	}
	}
