pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                dir 'test1'{
                    git 'https://github.com/zoom2x/test.git'
                    bat 'javac App.java && java App'
                }
                //git 'https://github.com/zoom2x/test.git'
                //bat 'cd /D D:\\java\\jenkins-java\\src && java App && javac App.java'
                
            }
        }
    }
}
