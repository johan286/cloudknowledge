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
 environment{
	location="paris"
 }
 steps { 
 	echo "this is Deploy stage"  
	echo " $location "
 } 
 } 
 stage('batch'){ 
 environment{
        location="landon"
 }

 steps{ 
	echo " predefined variable $BUILD_NUMBER $WORKSPACE " 
	echo " extrernal variable $name"
	echo " stage varible $location "
 } 
} 
}
}
