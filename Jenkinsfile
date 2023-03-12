pipeline{
    agent any
    stages {
        stage('check jenkins'){

        steps{
            sh '''
            chmod +x gunicorn.sh
            ./gunicorn.sh
            '''
            }
        }
    }
}   