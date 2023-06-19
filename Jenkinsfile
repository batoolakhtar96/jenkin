pipeline {
    agent any
    stages {
        stage('clone') {
            steps {
                git branch: 'main', url:'https://github.com/batoolakhtar96/jenkin.git' 
            }
        }
        stage("deploy")
            {
            steps
                {
                bat 'xcopy /s C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\f2 D:\\website'
                }
            }
        }
    }
    

