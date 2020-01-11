node{
    
    stage('clone java project') {
    git 'https://github.com/devopsvc/mahalogin.git'
    }
    
   stage('maven target') {
    bat label: '', script: 'mvn install'
    }
    
    
    
}
