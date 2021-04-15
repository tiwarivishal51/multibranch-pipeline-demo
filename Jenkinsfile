pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                echo 'building application....'
                }
            }

        stage ('Testing Stage') {
            when { 
               branch 'develop' 
              }

            steps {
                echo 'testing application....'
                }
        }


        stage ('Deployment Stage') {
            steps {
                echo 'deploying application....'
                }
            }
    }
}
