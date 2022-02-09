pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                script{
                    try {
                        echo "Hello World!";
                        def arr = new int[3];
                        arr[5] = 5;
                    } catch(Exception ex){
                        echo "exception caught";
                    }
                    echo "moving on";
                }
            }
        }
    }
}