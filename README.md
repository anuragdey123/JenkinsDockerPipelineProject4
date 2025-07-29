🚀 **Automated Docker Image Build & Push using Jenkins Pipeline (From Scratch)**  
Hey Tech Enthusiasts! 👨‍💻✨

I’m excited to share my latest DevOps hands-on project where I **built Jenkins from scratch (no pre-built image)** and used it to automate:

✅ Docker Image Creation  
✅ Pushing to a **Self-Hosted Docker Registry**  
✅ CI/CD pipeline with Jenkinsfile

---

🔧 **Tech Stack Used:**  
🐳 Docker  
🛠️ Jenkins (custom setup, not pulled)  
📦 Local Docker Registry (`localhost:5000`)  
📂 PowerShell + VS Code (Windsurf)  
🧾 Jenkinsfile pipeline automation

---

📌 **Project Flow:**  
1️⃣ Built Jenkins using a custom Dockerfile on Ubuntu base  
2️⃣ Created a sample Node.js app and Dockerized it  
3️⃣ Configured a local Docker registry using `docker-compose`  
4️⃣ Wrote a Jenkinsfile with 2 stages:  
   - 🛠️ `docker build`  
   - 📤 `docker push` to registry  
5️⃣ Ran Jenkins pipeline from scratch — NO IMAGE PULLING involved!

---

📁 **Project Folder Structure:**
JenkinsDockerPipelineProject/
├── app/ # Web app + Dockerfile
├── docker-registry/ # Local registry via docker-compose
├── jenkins-setup/ # Custom Jenkins Dockerfile
├── Jenkinsfile # CI pipeline script


🧠 This project made me truly understand:  
✔️ How Jenkins works internally  
✔️ End-to-end CI automation  
✔️ Manual setup of Jenkins + Docker + Registry  
✔️ Real industry-oriented DevOps challenges

