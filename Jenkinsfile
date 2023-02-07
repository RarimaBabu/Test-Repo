pipeline {
  agent none
  stages {
    stage('File saving stage') {
      steps {
        writeFile(file: 'testfile', text: 'this is just a text file to check whether the pipeline is working or not', encoding: 'utf8')
        readFile(file: 'testfile', encoding: 'utf8')
      }
    }

  }
}