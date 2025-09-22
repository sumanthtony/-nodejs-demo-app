# nodejs-demo-app
Setting up a CI/CD pipeline to build and deploy a web app using GitHub Actions

**TASK 1: Automate Code Deployment Using CI/CD Pipeline (GitHub Actions)**
Following steps taken to complete the task:
================================================

**===>**Created a new repository **nodejs-demo-app** launched EC2 instance and installed packages (Docker, Git)

**===>**Written the code initialized git, tracked the files, written **Dockerfile**, built the image and committed to master branch

**===>**Connected to remote repo and pushed the code using Classic token

<img width="636" height="155" alt="Generated_classic Token" src="https://github.com/user-attachments/assets/136a553d-6aa7-48d6-974b-472194add349" />

**===>**Created a **Github Actions** in **nodejs-demo-app** written **main.yaml code** and committed to main branch directly and the **CI/CD build** was successfull

<img width="443" height="398" alt="Github_Actions" src="https://github.com/user-attachments/assets/34d1a838-3222-43b0-991b-ce23e6352e7a" />

**===>**To create a container in **Docker** and push to **DockerHub** stored docker credentials in **github secrets** and used in **main.yaml**

<img width="866" height="281" alt="Docker_cred in Github" src="https://github.com/user-attachments/assets/6cb9afb8-98a2-416d-9336-d6b5846c6ba0" />

**===>**To access docker credentials created a personal access token

<img width="461" height="221" alt="Ref snapshot of dockerhub token" src="https://github.com/user-attachments/assets/999a6593-3265-4bee-8d72-2a845436ae51" />

**===>**Upon successsfull CI/CD pipeline is built **Docker Image** is stored in my **Dockerhub new Repository** and was able to access the application 

<img width="491" height="337" alt="Pushed image to dockerhub" src="https://github.com/user-attachments/assets/d56e4887-b033-4669-a50f-43c5de5bfb8d" />

<img width="818" height="358" alt="Debugging " src="https://github.com/user-attachments/assets/816bd276-5b53-4647-ae47-33b11ed6cb9a" />

--------------------------------THIS WAS THE FINAL OUTPUT-----------------------------------------------------------
<img width="383" height="79" alt="Nodejs_output" src="https://github.com/user-attachments/assets/cb4e3e4e-61d7-4ede-bfba-cad0ff64a528" />








