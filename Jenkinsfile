pipeline{
    agent any
    
    environment
    {
        GEM_HOME= "/home/vagrant/.rvm/rubies/ruby-2.6.3"
    }
    stages {
        stage('install'){
            steps {
                
                sh "gem install bundler -v 2.1.4"
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
