pipeline {
    agent {
        label 'python'
    }
    stages {
        stage('Run Python Script') {
            steps {
                sh 'python3 script.py'
            }
        }
    }
}


pipeline {
  agent {
      label 'python'
  }
  stages {
    stage('version') {
      steps {
        sh 'python --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python hello.py'
      }
    }
  }
}
