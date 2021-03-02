node {
    stage('SCM'){
        git credentialsId: 'github', url: 'https://github.com/cherukurisai451/webapp.git'
    }
    stage('BUILD') {
        sh 'mvn clean package'
    }
    stage ('TEST'){
        echo 'test'
    }
    stage('SCAN'){
        echo 'Scan'
    }
    stage ('deploy'){
        echo 'Deploy'
    }
}
