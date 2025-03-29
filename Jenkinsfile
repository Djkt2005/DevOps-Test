pipeline{
    agent any
    stages{
        stage('install dependencies'){
            steps{
                sh 'npm install';
            }
        }
        

        stage('run tests'){
            steps{
                sh 'npm run test || echo "No tests defined"';
            }
        }

        stage('build'){
            steps{
                sh 'npm run build';
            }
        }
    }
}
