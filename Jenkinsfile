pipeline{
    agent any
    stages {
        stage('install'){
            steps {
                
                sh "gem install saas"
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
