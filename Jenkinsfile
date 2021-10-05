node {
    stage('Preparation') { 
      echo "Get from source"
      git branch: 'main', url: 'https://github.com/Wernervdmerwe/automationscripts.git'
      sh 'bash run_demo.sh'
    }
    stage('Test') { 
      echo "Starting"
      sh 'hostname'
    }
    stage('UAT') { 
      echo "Starting"
      sh 'hostname'
    }    
}
