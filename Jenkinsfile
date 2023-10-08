pipeline {
    agent any

    stages {
        stage('test') {
            steps {
                echo 'testing'
            }
        }
      stage('build') {
            steps {
                echo 'building'
            }
        }
      stage('deploy') {
            steps {
                echo 'deploying'
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}
