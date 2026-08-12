pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
post{
        success{
            echo'pipeline executed succesfully!'
        }
        failure{
            echo'pipeline failed.Please check the logs for details.'
        }
}


