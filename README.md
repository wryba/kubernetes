# kubernetes
## install on windows with docker
Docker > Settings > Kubernetes > Enable

## install on linux
curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt                    - check latest stable version
curl -LO https://storage.googleapis.com/kubernetes-release/release/v1.24.1/bin/md64/kubectl     - install current version - v1.24.1 can differ :)
chmod +x ./kubectl                                                                              - change permissions to kubectl
sudo mv ./kubectl /usr/local/bin/kubectl                                                        - move it to local/bin

## vscode extensions
Kubernetes (M$)
Remote - WSL (M$)
Yaml (RedHat)

## basic commands
kubectl version         - checks currently installed version
