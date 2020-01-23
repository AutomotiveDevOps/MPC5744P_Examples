pipeline {
  agent any
  stages {
    stage('EnvTest') {
      steps {
        sh 'which bash'
        sh 'which python; python --version'
        sh 'which cmake; cmake --version'
        sh 'which git; git --version'
      }
    }

    stage('SetupEnv') {
      steps {
        sh 'sh setup_env.sh'
      }
    }

  }
}