pipeline {

    agent { label 'agent-Anant1' }
 
    stages {

        stage('Clone Repository') {

            steps {

                sh 'rm -rf bat_file || true'

                sh 'git clone -b main https://github.com/Anant-1209/batFileDocker.git'

                echo "Cloned..."

            }

        }

        stage('Run') {

            steps {

                echo "completed"

            }

        }

    }

}

 
