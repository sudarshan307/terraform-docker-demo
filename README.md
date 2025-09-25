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
