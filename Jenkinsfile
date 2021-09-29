node('nodejs') {
   stage('Checkout') {
       git branch: 'main', url: 'https://github/Yaroksito/do400-pipelines-control'
   }
   stage('Backend Tests') {
       sh 'node ./backend/test.js'
   stage('frontend Tsts') {
       sh 'node ./frontend/test.js'
   }
