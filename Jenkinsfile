pipeline {
    agent any
    parameters {
  choice choices: ['DEV', 'PRD'], description: 'Select Environment', name: 'ENV'
}

    stages {
        stage ('working with conditions') {
            steps {
                script {
                    val1 = 11
                    println "my val1 value is ${val1}"
                    println "my parameter value is ${params.ENV}"   

                }
            }
        }            
    }
}
