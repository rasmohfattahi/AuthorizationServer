mvn clean package 
mvn spring-boot:run
http://localhost:9000/oauth2/authorize?response_type=code&client_id=client-id&redirect_uri=http://localhost:9000/test/get-auth-code&scope=openid
Add basic auth. username is -> 'user' and password is -> 'password'
