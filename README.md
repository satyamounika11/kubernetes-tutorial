# kubernetes-tutorial
This repo consists of test files and commands to create K8s resources.

Minikube installation for Windows:
To install **Minikube** on a **Windows laptop**, here are the **pre-requisites** you need to have in place:

---

### ✅ 1. **Operating System**
- Windows 10 or 11 (64-bit)
- Either **Windows Home** or **Windows Pro**

---

### ✅ 2. **Hardware Requirements**
- At least **2 CPUs**
- **2GB RAM** minimum (4GB+ recommended)
- **20GB free disk space**
- Virtualization **enabled** in BIOS

---

### ✅ 3. **Package Manager**
- **[Chocolatey](https://chocolatey.org/install)** (recommended) or **[Scoop](https://scoop.sh)**
  (You can also download Minikube manually if you don’t want a package manager)

---

### ✅ 4. **Virtualization Support**
Choose **one** of the following **drivers** to run Minikube:

#### Option A: **Hyper-V** (Recommended for Windows Pro/Enterprise)
- Enable **Hyper-V** via “Turn Windows features on or off”
- Create a **virtual switch** in Hyper-V Manager

#### Option B: **Docker**
- Install **Docker Desktop** for Windows
- Enable Kubernetes (optional)

#### Option C: **VirtualBox**
- Install **Oracle VirtualBox**

> ⚠️ Note: Hyper-V and VirtualBox **cannot run simultaneously**, so choose only one.

---

### ✅ 5. **Install kubectl**
Install Kubernetes CLI:
```bash
choco install kubernetes-cli
```
Or download from [official site](https://kubernetes.io/docs/tasks/tools/install-kubectl/)

---

### ✅ 6. **Install Minikube**
With Chocolatey:
```bash
choco install minikube
```
Or download from [https://minikube.sigs.k8s.io/docs/start/](https://minikube.sigs.k8s.io/docs/start/)

---

### ✅ 7. **Enable Virtualization in BIOS**
Ensure virtualization (VT-x for Intel or AMD-V) is **enabled** in your system BIOS/UEFI.

---

Let me know which virtualization method you plan to use (Docker, Hyper-V, or VirtualBox), and I can help you set it up step-by-step.
