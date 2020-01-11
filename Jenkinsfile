node{
    
    stage('clone java project') {
    git 'https://github.com/devopsvc/mahalogin.git'
    }
    
   stage('maven target') {
    bat label: '', script: 'mvn install'
    }
    
    stage('eamil notification') {
    emailext body: 'heloo', subject: 'hi', to: 'maha42iac@gmail.com'
    }
    
    
    
}
