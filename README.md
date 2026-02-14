# AWS EC2 Docker Deployment - Hina Atif


🚀 **Welcome to My AWS EC2 Docker Deployment**  
This project demonstrates deploying a sample website on AWS EC2 using Docker.  
Designed, containerized, and deployed by **Hina Atif**.

> "Every deploy makes you stronger."

---

## 🔹 Project Overview
This project shows the full workflow of deploying a Dockerized web application on an AWS EC2 instance.  
It includes:

- Setting up an EC2 instance
- Installing Docker
- Building and running a Docker container
- Deploying a sample website
- Verifying deployment via browser

---

## 🔹 Folder Structure

AWS-EC2-DOCKER-DEPLOYMENT-HINA-ATIF/
│
├── docker/ # Dockerfile for web app
├── docs/ # Deployment guide (optional PDF)
├── sample_website/ # HTML website files
├── screenshots/ # Screenshots of EC2, Docker, website
└── README.md # Project documentation


---

### Screenshots

**EC2 Dashboard**  
<img width="884" height="92" alt="image" src="https://github.com/user-attachments/assets/0f298700-bc24-4e34-a996-1b90272be268" />


**Docker Build**  
<img width="1566" height="518" alt="image" src="https://github.com/user-attachments/assets/16c884a8-69af-4055-9bf6-8e2d911e7e97" />

**Docker Ps**
<img width="1600" height="218" alt="image" src="https://github.com/user-attachments/assets/f0d642d5-1c50-427c-8ab6-1d91f5c43169" />


**Website Preview**  
<img width="1424" height="447" alt="image" src="https://github.com/user-attachments/assets/84b8cb51-df4a-46ed-b178-74e12b5dad0c" />



---

## 🔹 Deployment Steps (Summary)

1. Launch AWS EC2 instance (Ubuntu or Amazon Linux)
2. SSH into the instance
3. Install Docker:

```bash
sudo apt update
sudo apt install docker.io -y   # For Ubuntu
sudo systemctl start docker
sudo systemctl enable docker
docker --version

---

Build Docker image:
cd ~/AWS-EC2-DOCKER-DEPLOYMENT-HINA-ATIF
docker build -t hina-atif-website -f docker/Dockerfile .

---

Run Docker container:
docker run -d -p 80:80 hina-atif-website
docker ps
Open browser → http://<EC2_PUBLIC_IP> → see your deployed website

---

🔹 Technologies Used

<img width="66" height="20" alt="image" src="https://github.com/user-attachments/assets/2934acf2-349a-467c-8f20-2db5d3ff0757" />

<img width="49" height="20" alt="image" src="https://github.com/user-attachments/assets/7f361c45-ee6a-4d39-ad3c-a00e9a4b59bc" />
---

🔹 Notes

Screenshots should reflect the actual deployment process.

The project demonstrates practical DevOps skills and cloud deployment.

Optional: Add PDF deployment guide in docs/ for recruiters.

---


Project completed by Hina Atif

"Every deploy makes you stronger."

---


---

# 🟢 Next Step — Push README.md to GitHub

1. Save this file as `README.md` inside your **local repo folder**.
2. Open Git Bash **in that folder**.
3. Run:

```bash
git add README.md
git commit -m "Add professional README.md"
git push origin main







