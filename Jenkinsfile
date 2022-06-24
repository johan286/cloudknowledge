pipeline { 
 agent any  
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
	bat "dir" 
 	bat "cd" 
	bat "ping www.google.com" 

 } 
} 

