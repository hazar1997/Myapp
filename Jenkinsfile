pipeline {
  agent any
    stages {
        stage('Pull') {
             steps{
                script{
                    checkout([$class: 'GitSCM', branches: [[name: '*/master']],
                        userRemoteConfigs: [[
                            credentialsId: '989dea40-b0fd-46e4-be14-0082313ba166',
                            url: 'https://github.com/hazar1997/Myapp.git']]])
                }
            }
        }
   	}
        }
