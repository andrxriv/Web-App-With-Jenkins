pipeline {
    agent any
    
    stages {
        stage('Clean'){
            steps {
                cleanWs()
            }
        }

        stage('Hello'){
            steps {
                echo 'Hello World!'
            }
        }
        // stage('W/O Docker'){
        //     steps {
        //         sh """
        //         ls -la
        //         touch container-no.txt
        //         """
        //     }
        // }
        
        // stage('Docker'){
        //     agent {
        //         docker {
        //             image 'node:18-alpine'
        //             reuseNode true
        //         }
        //     }
        //     steps {
        //         sh """
        //             echo "With Docker"
        //             ls -la
        //             touch container-yes.txt
        //         """
        //     }
        // }
    }
}