pipeline{
    agent any
    stages {
        stage('check jenkins')

        steps{
            sh '''
            chomd +x gunicorn.sh
            ./gunicorn.sh
            '''
        }
    }
}