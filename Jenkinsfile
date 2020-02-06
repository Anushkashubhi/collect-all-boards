pipeline{
agent any
stages{

stage('Jenkins job'){
 steps {
 sh '''
 curl -X GET \
  http://ec2-18-191-16-16.us-east-2.compute.amazonaws.com:8080/rest/agile/1.0/board \
  -H 'accept: application/json' \
  -H 'authorization: Basic cmlnOmRpZ2l0YWxyaWdAMTIz' \
  -H 'cache-control: no-cache' \
  -H 'postman-token: 43404ed5-8a50-2ac3-9671-418d226981e0'
 '''
 }
        }
        
 }
 }
