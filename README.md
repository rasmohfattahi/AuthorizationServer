# Mvn clean package 
mvn clean package 
# Run  
mvn spring-boot:run
# Test authorize endpoint to get an Authorization code. 
http://localhost:9000/oauth2/authorize?response_type=code&client_id=client-id&redirect_uri=http://localhost:9000/test/get-auth-code&scope=openid
# Test credential. 
Add basic auth. username is -> 'user' and password is -> 'password'
