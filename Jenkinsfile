pipeline { 
 agent any  
 environment{
	name="ARBAZ"
 }
 stages { 
 stage('Build') {  
 steps { 
  	echo "this is build stage"  
 } 
 } 
 stage('Test') {  
 steps { 
 	echo "this is Test stage"  
 } 
 } 
 stage('Deploy') {  
 steps { 
 	echo "this is Deploy stage"  
 } 
 } 
 stage('batch'){ 
 steps{ 
	echo " predefined variable $BUILD_NUMBER $WORKSPACE " 
	echo " extrernal variable $name
 } 
} 
}
}
