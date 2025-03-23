# Ansible

# 🛠️ Ansible Playbook Generator with Python  

## 🚀 Overview  
This project automates the installation of various DevOps tools using **Ansible**. A **Python script** allows users to **select tools from a list**, and it generates an **Ansible playbook** (`install_tools.yml`) based on their choices. This ensures a streamlined and efficient setup of infrastructure components.  

## 🔹 Features  
- **Dynamic Tool Selection** – Choose the tools you need via an interactive command-line menu.  
- **Automated Ansible Playbook Generation** – No need to manually edit YAML files.  
- **Simple Execution** – Just run the generated Ansible playbook to install everything.  

## 📦 Supported Tools  
This script can generate Ansible tasks for installing:  
✔ **Programming & Runtime Environments**  
  - Node.js & npm  
  - Java  
  - Python  
  - .NET SDK  

✔ **Cloud CLI Tools**  
  - AWS CLI  
  - Azure CLI  
  - Google Cloud CLI (GCP)  

✔ **Databases**  
  - MySQL  
  - PostgreSQL  
  - MongoDB  

✔ **DevOps & CI/CD Tools**  
  - Git  
  - Docker  
  - Kubernetes (kubectl, kubeadm, kubelet)  
  - Helm  
  - SonarQube & SonarScanner  
  - ELK Stack (Elasticsearch, Logstash, Kibana)  
  - Ansible  
  - Terraform  
  - Prometheus & Grafana  

✔ **Utilities**  
  - zip & unzip  
  - wget  
  - tree  
  - top  
  - nginx  

## 📌 How to Use  

1️⃣ Install Dependencies  

Ensure you have Python and Ansible installed:  
```sh
sudo apt update && sudo apt install -y python3 ansible

2️⃣ Run the Python Script
python3 generate_ansible.py
Follow the on-screen prompts to select the tools you need.

3️⃣ Run the Generated Ansible Playbook
Once the playbook (install_tools.yml) is generated, run:

ansible-playbook install_tools.yml
Ansible will handle the installation of all selected tools! 🎯

🎯 Why Use This?
Saves time configuring infrastructure

Ensures consistency across different environments

Automates DevOps tool installations

Works across various Linux-based systems

🤝 Contributing
Feel free to submit pull requests for improvements, new tools, or additional features!

