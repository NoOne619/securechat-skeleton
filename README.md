readme_content: |
  # SecureChat: A PKI-Enabled Chat System
  
  This project is a console-based, secure chat system built in Python. It implements an application-layer protocol to ensure **Confidentiality, Integrity, Authenticity, and Non-Repudiation (CIANR)** for all messages, using a custom Public Key Infrastructure (PKI).
  
  **GitHub Repo:** [https://github.com/NoOne619/securechat-skeleton](https://github.com/NoOne619/securechat-skeleton)
  
  ---
  
  ## ⚙️ Configurations Required
  
  Before running the application, you must set up the environment, database, and cryptographic keys.
  
  ### 1. Environment & Dependencies
  
  First, clone the repository, create a Python virtual environment, and install the required packages.
  
  ```bash
  # Clone the repository
  git clone [https://github.com/NoOne619/securechat-skeleton.git](https://github.com/NoOne619/securechat-skeleton.git)
  cd securechat-skeleton
  
  # Create and activate a virtual environment
  python3 -m venv .venv
  source .venv/bin/activate
  
  # Install dependencies
  pip install -r requirements.txt
