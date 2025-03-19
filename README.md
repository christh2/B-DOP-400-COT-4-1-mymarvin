This README includ how to test the project my_marvin
- First : sudo docker build -t jenkins:jcasc .
- Second : sudo docker run --name jenkins --rm -p 8080:8080 --env-file text.env jenkins:jcasc
  
After this 
- Go to any search engine and seach LOCALHOST : 8080
- And now you can access to the authentification page and enter a user and password to connect
