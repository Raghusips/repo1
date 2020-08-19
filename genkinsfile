pipeline {
  agent any
  stages {
  stage('Build') {
    steps {
      sh 'echo "file1.sh is executed "'
      sh 'chmod 777 file1.sh'
      sh './file1.sh'
    }
  }
}
}
