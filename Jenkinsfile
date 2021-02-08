pipeline {
  agent any
  stages {
    stage('Upload') {
      agent {
        node {
          label 'Local'
        }

      }
      steps {
        bat(script: '"D:\\\\UwaProjScan\\\\UwaServiceUploader\\\\UwaServiceUploader.exe" "PA" "RTpcQW50TWFuQW5kcm9pZERldlxQcm9kdWN0XEFwcHNcQW5kcm9pZFwyMDIwMTBcQW50TWFuXzgxNTAwLmFwaw==" "%BUILD_ID%" "QnVpbGRBbmRVcGxvYWQ=" "bWFpbg==" "NjIxNQ==" "dHJ1ZQ==" "NywyNCwyOA==" "NCwz" "MQ=="', encoding: '', label: '', returnStatus: '', returnStdout: '')
      }
    }

  }
}