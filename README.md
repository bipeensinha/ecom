This lab demonstrates how to build, store, and deploy containerized applications using Azure Container Registry (ACR) and Azure Web App for Containers.

git clone https://github.com/bipeensinha/ecom.git
cd e-com
ls
docker pull nginx:alpine
docker build -t bipecom .
docker images
docker run -d -p 8080:80 --name ecom bipecom

<img width="1017" height="517" alt="image" src="https://github.com/user-attachments/assets/a633d3de-35da-48ca-bd93-bf1ba72e2d91" />
