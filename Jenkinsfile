node() {  
    stage('Build') { 
        // 
        echo 'a'
    }
    stage('Test') { 
        // 
        echo 'b'
        bat label: '', script: 'robot --pythonpath yjyx --test *5101 yjyx/tc'
    }
    stage('Deploy') { 
        // 
        echo 'd'
    }
    stage(‘test'){
    	//
	echo 'd'
    }
}
