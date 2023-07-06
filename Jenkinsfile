pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/job1']], userRemoteConfigs: [[url: 'https://github.com/Bounzeback/jenkinsjobs.git']]])
            }
        }
        stage('1-member1') {
            steps {
                echo "ifeanyi"
            }
        }
        stage('2-member2') {
            steps {
                echo "Marius"
            }
        }
        stage('3-member3') {
            steps {
                echo "Kingsley"
            }
        }
        stage('4-member') {
            steps {
                echo "Ronald"
            }
        }
    }
}
