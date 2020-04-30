node('UBUNTU2'){
    stage('GIT'){
        git 'https://github.com/resourceelabb/JenkinsBuildPractice.git'
    }
    stage('Package'){
         sh 'mvn package'
    }
    stage('Archive artifacts'){
         archive 'gameoflife-web/target/*.war'
    }
} 