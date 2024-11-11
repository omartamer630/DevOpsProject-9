

# Tooling Website Deployment Automation With Continuous Integration
![184101792-3c29fba2-78dd-4333-8aee-3385c605ecf1](https://github.com/user-attachments/assets/a7c2af19-df0d-420b-8cb5-b03687de88c9)

## Steps
 1- 7 EC2 one for NFS Server, One for DB Server, Three for serving website with apache, One for Load Balancing, One for Jenkins ![image](https://github.com/user-attachments/assets/24c4bb2e-0483-4df7-9a5b-ac7fdf0a7d0d)
 2- Created 3 Volumes 10GIB Each for NFS Server ![image](https://github.com/user-attachments/assets/3747b3e8-e344-4f3a-9ad7-4b639eae7b39)
 3- Installed SQL for DB Server and created DB
 ![image](https://github.com/user-attachments/assets/f60e94cb-54f4-4229-90da-dffc13900481)
 4- Connected Every websever EC2 to by allowing mysql port and Private IP 
 ![image](https://github.com/user-attachments/assets/a4e2e03f-6312-453f-82d1-be334d3d3204)
 5- Configure LB with ```bash file apacheLB.conf```
[Video for LB](https://github.com/user-attachments/assets/a543e169-afa9-473c-8757-b59bbf190c7f)
 6- Configure Jenkins Using Freestyle Pipeline and github cred webhook and using Public for SSH plugin to connect to NFS Server and deploy any feature for both Webserver
 ![image](https://github.com/user-attachments/assets/bb4dd6cd-2897-47fa-81b8-50b19f49cf9e)
 ![image](https://github.com/user-attachments/assets/446074c6-c533-409f-8106-f8381de22318)

## Result
   https://github.com/user-attachments/assets/b45adc59-9387-497f-bf58-d10a6673b455
 # ![image](https://github.com/user-attachments/assets/3ff5ff2a-8e9c-4ad7-8371-356d257e703c)
 # ![image](https://github.com/user-attachments/assets/aa409a23-8a9b-43de-8498-84a0f4ef72c2)
 # ![image](https://github.com/user-attachments/assets/fb5ff22e-e9d5-4a6d-a656-822f96fdfc4d)




