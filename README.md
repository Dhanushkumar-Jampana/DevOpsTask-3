# 🚀 Task 3: Infrastructure as Code (IaC) with Terraform

## 📚 Objective
Provision a **local Docker container** using **Terraform**, applying the concepts of Infrastructure as Code.

---

## 🛠 Tools Used
- **Terraform**
- **Docker**

---

## 📂 Files Included

- `main.tf` – Terraform configuration file
- (Optional) `variables.tf` – Variables used in the config
- (Optional) `outputs.tf` – Outputs after deployment
- `README.md` – Project documentation

---

## ⚙️ Steps to Run the Project

1. **Clone the Repository**
```bash
git clone https://github.com/<your-username>/terraform-docker-provision.git
cd terraform-docker-provision
```

2. **Initialize Terraform**
```bash
terraform init
```

3. **Check the Execution Plan**
```bash
terraform plan
```

4. **Apply Configuration to Provision Container**
```bash
terraform apply
```

5. **Verify**
Go to `http://localhost:<your-port>`  
*(Make sure Docker is running and the port is not already in use.)*

6. **Destroy Infrastructure**
```bash
terraform destroy
```

7. **Check State (Optional)**
```bash
terraform state list
```

---
<img width="1920" height="1080" alt="Screenshot (106)" src="https://github.com/user-attachments/assets/83b0fe11-1a28-414f-894d-3a44f589206c" />

## 🎯 Outcome
<img width="1920" height="1080" alt="Screenshot (106)" src="https://github.com/user-attachments/assets/b834c493-2cad-44de-9190-f3de65a89996" />


By completing this task, you'll understand how to:
- Use Terraform Docker provider
- Write Terraform scripts for local containers
- Apply and destroy infrastructure
- Manage infrastructure state

---
