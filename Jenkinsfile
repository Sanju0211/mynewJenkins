pipeline {
      agent any
      stages {
            stage('Checkout') {
                  steps {
                        git branch: 'develop', url: 'https://github.com/Sanju0211/mynewJenkins.git'
                  }
            }
            stage('Pull to Folder') {
                  steps {
                        sh 'mkdir -p folder'
                        sh 'cp -r * folder'
                  }
            }
      }
}
