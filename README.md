# DevOps Project(TOOLING WEBSITE SOLUTION)
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

## Result
 # ![image](https://github.com/user-attachments/assets/aa409a23-8a9b-43de-8498-84a0f4ef72c2)
 # ![image](https://github.com/user-attachments/assets/fb5ff22e-e9d5-4a6d-a656-822f96fdfc4d)

