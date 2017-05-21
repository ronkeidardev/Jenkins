#!/usr/bin/env groovy
/**
* This is an pipeline example
*/
// Load Libraries as needed
//
//library ('git@github.com/ronkeidardev/Jenkins')

//import com.verint.*;
//import com.verint.devops.core.Logger ;

/// Properties
//def lib= Library('CI_workflowLibs-r').com.verint.devops.core.Logger
//def l = new com.verint.devops.core.Logger()

//z.checkOutFrom(repo)

pipeline {
    agent  { node { label 'master' } }
    stages {
        stage('Start') {
            steps {
                //zTest.testMethod("111")
                // send build started notifications
                //   sendNotifications 'STARTED'
                //     repo = "DEVOPS_Utils"
                bat 'echo in start steps'
                //l=   lib.Logger.new(steps)
                //    echo l.LogLevel
                echo 'end"'
            }

        }

    }
    post {
        always {
            echo currentBuild.result
        }
    }
}
