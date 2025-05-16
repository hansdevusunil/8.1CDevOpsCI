pipeline {
  agent any

  stages {
    stage("Build") {
      steps {
        bat 'echo Using Maven to compile and package the code'
      }
    }

    stage("Unit and Integration Tests") {
      steps {
        bat 'echo Using JUnit and Postman for unit and integration testing'
      }
    }

    stage("Code Analysis") {
      steps {
        bat 'echo Using SonarQube for code quality analysis'
      }
    }

    stage("Security Scan") {
      steps {
        bat 'echo Using OWASP Dependency-Check for security scanning'
      }
    }

    stage("Deploy to Staging") {
      steps {
        bat 'echo Deploying to AWS EC2 instance (staging)'
      }
    }

    stage("Integration Tests on Staging") {
      steps {
        bat 'echo Running integration tests on staging environment using Postman'
      }
    }

    stage("Deploy to Production") {
      steps {
        bat 'echo Deploying to AWS EC2 instance (production)'
      }
    }
  }
}
