node {
    stage('Clone') {
        git branch: 'main', url: 'git@github.com:CBA2108/projet1.git'
    }
    stage('Build') {
       sh label: '', script: 'javac Main.java'
    }
    stage ('Run') {
       sh label: '', script:     'java Main'
    }
}
