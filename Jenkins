pipeline {
    agent any

    stages {
        stage('BUild') {
            steps {
                echo 'Building'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying'
            }
        }
    }
    post{
        always
        {
            emailext body: 'gugukku', subject: 'hii', to: 'vilas147854@gmail.com'
        }
    }
    
}
