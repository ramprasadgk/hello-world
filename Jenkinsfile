@Library('test') _

pipeline {
    agent none
    stage ('git') {
        steps {
            // log.info 'Starting' 

            echo myFile("Mark Turner")
            // or
            echo myFile.slack_handle("Mark Turner")
             myFile.otherMethod()
            script { 
                log.info 'Starting'
                log.warning 'Nothing to do!'
            }
        }
    }
}