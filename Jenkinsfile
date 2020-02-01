    @Library('test') _

    pipeline {
        agent any
        stages{
            stage ('git') {
                steps {
                    // log.info 'Starting' 

                    checkout scm
                    //my.otherMethod()
                
                        echo my("Mark Turner")
                    // or
                    echo my.slack_handle("Mark Turner")
                    
                        withCheckout(scm) {
                            echo "GIT_COMMIT is ${env.GIT_COMMIT}"
                        
                    }
                }
            }
        }
    }