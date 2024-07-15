# Proctor: Full Stack Application
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
# Backend
## Available Scripts


# BackEnd

# MonitorApplication
2 TABLES
ipPort entities ip_address , portno
userDetails entities email , tokenid, ip_port_id(one to one) mapped with ipPort TABLE ,
HENCE SAME IPADDRESS AND PORT NO IS ADDED IN BOTH TABLES WITH SAME ID

Scheduler = 1 sec

JSON BODY 
Eg: /adddetails

{
  "token_id": "abcdefghijk1234567",
  "email": "meganitish@gmail.com",
  "ipPort": {
  "ipAddress": "172.16.3.250" ,
    "port": 6969
  }
}

![image](https://github.com/user-attachments/assets/06d8bd7d-ab98-490a-a32c-e40da171ca0b)

