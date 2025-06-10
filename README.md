# MLOps-CI-Prac
Repository to practice CI (Continuous Integration) MLOps

## 📘 Continuous Integration (CI) - Quick Notes

### 🔹 Introduction  
Continuous Integration (CI) is a development practice where developers frequently merge code into a shared repository. Each merge triggers an automated process to build and test the code, ensuring smooth integration.

---

### 🔹 Why CI?  
- **Early Error Detection**: Catch and fix issues early.  
- **Automated Testing**: Maintains high code quality.  
- **Faster Development**: Enables quick feedback and iterations.  
- **Fewer Integration Issues**: Reduces complexity over time.

---

### 🔹 How CI Works  
- **Version Control (VCS)**: Developers push code to platforms like GitHub or GitLab.  
- **CI Server**: Tools like GitHub Actions or Jenkins detect changes.  
- **Build Automation**: Code is compiled and prepared.  
- **Automated Testing**:
  - **Unit Tests**: Test individual components.
  - **Integration Tests**: Ensure components work together.
  - **End-to-End Tests**: Simulate real-world scenarios.
- **Feedback**: Build/test results are reported back to developers.

---

### 🔹 Benefits of CI  
- **Improved Code Quality**: Fewer bugs and regressions.  
- **Faster Delivery**: Quicker feature releases and fixes.  
- **Collaboration**: Easier teamwork and code sharing.  
- **Reduced Risk**: Early bug detection prevents big issues.

---

### 🔹 CI Workflow with GitHub Actions  
- **Triggering CI**: Starts on events like code push or pull request.  
- **Configuration**: Uses YAML files (e.g., `.github/workflows/ci.yaml`).  
- **CI Pipeline Steps**:
  - `Checkout Code`: Get the latest code from the repo.
  - `Set Up Environment`: Install dependencies.
  - `Run Tests`: Execute all tests.
  - `Build Artifacts`: If tests pass, create build files.
  - `Deploy`: (Optional) Push to staging or production.

---
