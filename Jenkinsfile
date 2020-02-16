pipeline{
    agent any
    stages {
        stage('install'){
            steps {
                
                sh gem install bundler -v 2.0.1
            }
        
        
        }

        
        stage('build') {
            steps {
                sh 'bundle install'
            }
        }
        stage('test'){
            steps {
                sh 'rake'
            }
        }
    }

}
