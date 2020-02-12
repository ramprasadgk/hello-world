    @Library('test') _
    import org.paya.jenkinslib.*

    pipeline {
        agent any
        stages{
            stage ('git') {
                
                    // log.info 'Starting' 

                steps{
                    echo new GetCommitInfo().isBranchIndexingCause().toString()
                
                    //echo my("Mark Turner")
                    // or
                    echo my.slack_handle("Mark Turner")
                    echo new GetCommitInfo().getCommitId()
                    //echo prime.parallelize(5)
                    //echo prime.parallelize(2)
                    //echo prime.parallelize(4)
                }
                
            }
        }
    }
