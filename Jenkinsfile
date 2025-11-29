pipeline {
    agent any
    parameters {
  choice choices: ['dev', 'prod', 'sit', 'uit'], description: 'reqired envs', name: 'ENV'
}

    stages {
        stage('code chekout') {
            steps{
                script {
                    println "hello all welcome"
                    var1 = 230
                    println "my var1 value is ${var1}"
                    /*accessing the paramerts*/
                    println "the selected env is ${params.ENV}"
                }
            }
        }
    }
}
