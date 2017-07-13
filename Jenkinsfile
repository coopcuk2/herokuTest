node {
stage('Preparation'){
git 'https://github.com/coopcuk2/herokuTest.git'
}
stage('Build'){
sh "./gradlew clean test"
}
stage('Deploy'){
sh. "git push https://git.heroku.com/immense-taiga-39900.git"
}
}
