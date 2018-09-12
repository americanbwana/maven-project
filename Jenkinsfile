pipeline {
    agent any

    tools {
      maven 'localMVN'
    }

    stages {
      stage{
        steps {
          sh 'mvn clean package'
        }
      }
    }
}
