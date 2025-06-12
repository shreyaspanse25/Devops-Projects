# 🚀 Flask Web App with Azure DevOps CI/CD

This is a simple Flask-based web application deployed to **Azure App Service** using an **automated CI/CD pipeline with Azure DevOps**. The project demonstrates end-to-end DevOps implementation using GitHub, Azure Pipelines, and automated deployment workflows.

---

## 🛠 Tech Stack

- **Backend:** Python (Flask)
- **CI/CD:** Azure DevOps Pipelines
- **Hosting:** Azure App Service (Linux)
- **Version Control:** GitHub
- **Scripting:** PowerShell, YAML
- **Testing:** Python `unittest`

---

## 🔧 Features

- ☁️ Cloud-hosted on Azure Web App (Linux)
- ✅ CI/CD pipeline with Azure DevOps
- 🔁 Auto-deployment on push to `main`
- 🧪 Integrated unit testing in pipeline
- 🔐 Secrets managed via Azure DevOps service connections
- 📦 Modular and production-ready folder structure

---

## 📁 Project Structure

```
flask-azure-app/
│
├── app.py                  # Main Flask app
├── requirements.txt        # Python dependencies
├── templates/
│   └── index.html          # HTML Template
├── tests/
│   └── test_app.py         # Basic unit test
├── azure-pipelines.yml     # CI/CD pipeline definition
└── .gitignore
```

---

## 🚀 Deployment Workflow (CI/CD)

1. **Push code to GitHub**
2. **Azure Pipeline triggers**:
   - Installs dependencies
   - Runs unit tests
   - Deploys to Azure App Service using the AzureWebApp task
3. **Production-ready deployment** within minutes

---

## ⚙️ How to Use

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/flask-azure-app.git
cd flask-azure-app
```

### 2. Run locally

```bash
pip install -r requirements.txt
python app.py
![image](https://github.com/user-attachments/assets/82774fb0-87c6-4408-b672-7ce054240a11)

```

---

## 📦 Azure DevOps Setup

- Create a **service connection** in Azure DevOps to your Azure subscription.
- Replace placeholders in `azure-pipelines.yml`:
  ```yaml
  azureSubscription: '<******************>'
  appName: '<flask-azure-app>'
  ```
- Push code to GitHub → CI/CD will auto-trigger

---

## 🙌 Author

**Shreyas Panse**  
[LinkedIn](https://www.linkedin.com/in/shreyas-panse-3a68a916a/) • DevOps Enthusiast • Atos | Eviden

---

## 📄 License

This project is licensed under the MIT License.
