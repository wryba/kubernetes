# kubernetes

## 1. Install

### 1.1 Install on windows with docker
Docker > Settings > Kubernetes > Enable

### 1.2 Install on linux
curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt                    - check latest stable version
curl -LO https://storage.googleapis.com/kubernetes-release/release/v1.24.1/bin/md64/kubectl     - install current version - v1.24.1 can differ :)
chmod +x ./kubectl                                                                              - change permissions to kubectl
sudo mv ./kubectl /usr/local/bin/kubectl                                                        - move it to local/bin

### 1.3 vscode extensions
Kubernetes (M$)
Remote - WSL (M$)
Yaml (RedHat)

## 2. Basic commands
kubectl version         - checks currently installed version
