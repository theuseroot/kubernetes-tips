# KUBERNETES TIPS AND COMMANDS
Tips and commands for managing and troubleshooting Kubernetes clusters.
# Get the number of pods running
kubectl get pods
# Get the number of running pods with details of every pod
kubectl get pods -o wide
# Get the number of running pods with details of every pod with namespace
kubectl get pods -o wide -n namespace
