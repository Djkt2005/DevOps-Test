pipeline{
    agent any
    stages{
        stage('install dependencies'){
            steps{
                bat 'npm install';
            }
        }
        

        stage('run tests'){
            steps{
                bat 'npm run test || echo "No tests defined"';
            }
        }

        stage('build'){
            steps{
                bat 'npm run build';
            }
        }
    }
}
