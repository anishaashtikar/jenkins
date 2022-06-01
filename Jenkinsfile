pipeline {

agent any

stages {

stage('Build') {

steps {

bat 'javac file.java'
  bat 'java -version'

}

}

stage('Run') {

steps {

bat 'java file'
}
}
}
}
