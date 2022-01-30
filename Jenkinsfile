node {
    stage('clone') {
        git 'https://github.com/namkant/mesdrives.git'    
    }
    stage('build') {
        sh 'javac Main.java'
    }
    stage('run') {
        sh 'java Main'   
    }
}
