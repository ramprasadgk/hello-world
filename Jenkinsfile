@Library('test') _

pipeline {
    agent none
    stages{
        stage ('git') {
            steps {
                // log.info 'Starting' 

                echo my("Mark Turner")
                // or
                echo my.slack_handle("Mark Turner")
                my.otherMethod()
                script { 
                    log.info 'Starting'
                    log.warning 'Nothing to do!'
                }
            }
        }
    }
}