### step1 
create certificate and config https and ldap: 

openssl req -new -newkey rsa:2048 -nodes -keyout TIG.project.com.key -out TIG.project.com.csr

config grafana.ini load the certificate

### step2 
config alert: 

Research keyword [smtp] grafana.ini and config the sender email address

### step3
docker-compose up -d

### step4
config database 

### step5
input dashboard template

### step6
Configure the recipient of the alert in the template