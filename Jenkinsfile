pipeline {
  agent any
    stages {
      stage ('clone') {
        steps {
          git url:'https://github.com/Harshithaa55/demo1.git',
            branch:'main'
        }
      }
      stage ('Run script') {
        steps {
          sh 'chmod +x script.sh'
          sh './script.sh'
        }
      }
    }
}
