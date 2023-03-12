pipeline{
    agent any
    stages {
        stage('check jenkins')
        {
            sh '''
            chomd +x gunicorn.sh
            ./gunicorn.sh
            '''
        }
    }
}