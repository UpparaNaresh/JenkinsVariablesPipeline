pipeline {
    agent any
    stages {
        stage ('Deploy-dev') {
            steps {
                echo 'Hello my develpoment has been completed'
            }
        }
   stage ('deploymemnt quzlity') {
        steps {
            echo 'Quality analysis'
            input 'Does the staging envirnoment looks everything OK?'
        }
   }
    
    stage ('Deploy-prod') {
        steps {
            echo 'Deploy the production'
        }
    }
}
}
