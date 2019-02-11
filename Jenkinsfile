pipeline {
    triggers {
        pollSCM(env.BRANCH_NAME != 'master' ? 'H/2 * * * *' : '')
    }
    agent none

    stages{
        stage('Validation') {
            steps {
                echo "chi"
            }          
        }
    }
}
