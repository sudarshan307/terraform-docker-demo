# terraform-docker

# 🚀 Infrastructure as Code (IaC) with Terraform and Docker

This project demonstrates how to provision and manage **Docker containers** using **Terraform** as Infrastructure as Code (IaC).  
We use the `kreuzwerker/docker` Terraform provider to pull an image (Nginx) and run it inside a container locally.

---

## 📌 Objectives
- Learn how to use Terraform with Docker.
- Provision an **Nginx container** automatically.
- Understand core Terraform commands (`init`, `plan`, `apply`, `destroy`).
- Manage infrastructure lifecycle with Terraform state.

---

## 🛠️ Tools & Prerequisites
- [Terraform](https://developer.hashicorp.com/terraform/downloads) (>=1.5.x)
- [Docker](https://docs.docker.com/get-docker/)
- GitHub (for version control)

Check installation:

terraform -version

docker --version

#Installing Terraform on Ubuntu cli :

<img width="1716" height="751" alt="Screenshot 2025-09-25 151511" src="https://github.com/user-attachments/assets/2bda66db-085c-4f6b-877d-e69d33447d6c" />

#Terraform Initialization by "terraform init" command :

<img width="1326" height="675" alt="Screenshot 2025-09-25 182125" src="https://github.com/user-attachments/assets/53aa75a3-5047-4dc4-9c1f-4fbcfdd553a9" />

#nginx webpage ran successfully on apache server :

<img width="1499" height="565" alt="Screenshot 2025-09-25 182822" src="https://github.com/user-attachments/assets/f4253b2f-4169-46e7-af7a-9cf06da8cc5c" />

#Terraform apply :

<img width="1697" height="800" alt="Screenshot 2025-09-25 183125" src="https://github.com/user-attachments/assets/8a6b36d8-00a8-408d-ae1e-8e5d8ee49e67" />

#Terraform destroy :

<img width="1702" height="810" alt="Screenshot 2025-09-25 183111" src="https://github.com/user-attachments/assets/8d5ee850-5807-4472-b22a-20759347aca9" />

