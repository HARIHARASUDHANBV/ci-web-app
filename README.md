**# 🚀 CI/CD Deployment to EC2 using GitHub Actions**



**This project demonstrates a simple yet powerful Continuous Integration and Continuous Deployment (CI/CD) pipeline that automatically deploys a static web application to an AWS EC2 instance using \*\*GitHub Actions\*\*.**



**## 📁 Project Structure**



**web-app/**

**├── index.html # Web page deployed to EC2**

**├── README.md # Project documentation**

**└── .github/**

**└── workflows/**

**└── deploy.yml # GitHub Actions workflow**







**## 🌐 What It Does**



**- Hosts a basic static website (index.html)**

**- Triggers GitHub Actions on every push to `main` branch**

**- Uses SSH to connect to EC2 instance**

**- Copies updated `index.html` file to EC2 via `scp`**

**- Restarts web server (`nginx` or `httpd`) on EC2**

**- Publicly accessible via EC2 Public IP on port 80**



**## ⚙️ Technologies Used**



**- \*\*GitHub Actions\*\* – for CI/CD workflow automation**

**- \*\*AWS EC2 (Ubuntu or Amazon Linux 2)\*\* – hosting the website**

**- \*\*NGINX or Apache (httpd)\*\* – simple web server**

**- \*\*Shell \& PowerShell\*\* – scripting and setup**



**## 🔐 GitHub Secrets Used**



**| Name              | Description                           |**

**|-------------------|----------------------------------------|**

**| `EC2\_PUBLIC\_IP`   | Public IP of your EC2 instance         |**

**| `SSH\_USERNAME`    | EC2 login user (e.g., `ubuntu`)        |**

**| `SSH\_PRIVATE\_KEY` | Contents of your `.pem` file (private key) |**



**## 🚀 How to Use**



**1. Launch EC2, install NGINX or Apache**

**2. Clone this repo and edit `index.html`**

**3. Commit and push changes to `main`**

**4. GitHub Actions will deploy your update automatically**



**## 📸 Deliverables**



**- ✅ Deployed web page via EC2 public IP**

**- ✅ GitHub Actions workflow passing**

**- ✅ Screenshots of:**

  **- Web app on browser**

  **- GitHub Actions pipeline**

  **- Repo structure**



**## 🧹 Cleanup**



**- Stop and terminate EC2 after testing to avoid AWS charges**

**- Remove GitHub secrets if the repo is public**



**---**



**\*\*Author:\*\* HARIHARASUDHAN B V**

  



