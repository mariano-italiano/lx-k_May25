## Kubernetes Install Notes

### Master node / Control plane

1. Włączenie modułów.
2. Konfiguracja kernela - sysctl.
3. Wyłączenie SWAPa.
4. Instalacja container runtime (containerd).
5. Dodanie repo K8s i instalacja pakietów kubeadm/kubelet/kubectl.
6. Inicjalizacja klastra - KUBEADM INIT.
7. Installacja pluginu sieciowego. 

### Worker node / Data plane

1. Włączenie modułów.
2. Konfiguracja kernela - sysctl.
3. Wyłączenie SWAPa.
4. Instalacja container runtime (containerd).
5. Dodanie repo K8s i instalacja pakietów kubeadm/kubelet/kubectl.
6. Dołączenie node'a do istniejącego klastra - KUBEADM JOIN.

Punkty 1-5 --> wykonanie skryptu `deploy-k8s.sh`
