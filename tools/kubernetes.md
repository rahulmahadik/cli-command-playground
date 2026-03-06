# Kubernetes Commands Cheatsheet

> Kubernetes is a container orchestration platform. Deploy, scale, and manage containerized apps across clusters.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `kubectl version` | Display client and server versions |
| `kubectl cluster-info` | Display cluster endpoint information |
| `kubectl api-resources` | List all available API resources |
| `kubectl api-versions` | List all available API versions |
| `kubectl get pods` | List all pods in the namespace |
| `kubectl describe pod` | Show detailed pod information |
| `kubectl delete pod` | Delete a specific pod |
| `kubectl exec` | Execute a command inside a pod |
| `kubectl run` | Create and run a pod from an image |
| `kubectl cp` | Copy files between pod and local machine |
| `kubectl get deployments` | List all deployments |
| `kubectl create deployment` | Create a new deployment |
| `kubectl scale` | Scale a deployment replica count |
| `kubectl rollout` | Manage deployment rollouts |
| `kubectl set image` | Update container image in a deployment |
| `kubectl autoscale` | Auto-scale a deployment based on metrics |
| `kubectl get services` | List all services |
| `kubectl expose` | Expose a resource as a service |
| `kubectl port-forward` | Forward local port to a pod |
| `kubectl get ingress` | List all ingress resources |
| `kubectl create service clusterip` | Create a ClusterIP service |
| `kubectl create service nodeport` | Create a NodePort service |
| `kubectl create service loadbalancer` | Create a LoadBalancer service |
| `kubectl get configmaps` | List all config maps |
| `kubectl create configmap` | Create a config map |
| `kubectl get secrets` | List all secrets |
| `kubectl create secret` | Create a secret resource |
| `kubectl get namespaces` | List all namespaces |
| `kubectl create namespace` | Create a new namespace |
| `kubectl config` | Modify kubeconfig settings |
| `kubectl logs` | Print logs from a container |
| `kubectl top` | Display resource usage metrics |
| `kubectl get events` | List cluster events |
| `kubectl get all` | List all resources in the namespace |
| `kubectl label` | Add or update resource labels |
| `kubectl delete` | Delete resources by name or selector |
| `kubectl create job` | Create a job resource |
| `kubectl create cronjob` | Create a cron job resource |
| `kubectl create ingress` | Create an ingress resource |
| `kubectl create role` | Create a role resource |
| `kubectl create rolebinding` | Create a role binding |
| `kubectl create clusterrole` | Create a cluster role |
| `kubectl create clusterrolebinding` | Create a cluster role binding |
| `kubectl create serviceaccount` | Create a service account |
| `kubectl create pdb` | Create a pod disruption budget |
| `kubectl create quota` | Create a resource quota |
| `kubectl get nodes` | List all cluster nodes |
| `kubectl describe node` | Show detailed node information |
| `kubectl cordon` | Mark a node as unschedulable |
| `kubectl uncordon` | Mark a node as schedulable |
| `kubectl drain` | Drain a node for maintenance |
| `kubectl taint` | Add or remove node taints |
| `kubectl apply` | Apply configuration from a file |
| `kubectl edit` | Edit a resource in-place |
| `kubectl get -o yaml` | Output resource definition as YAML |
| `kubectl diff` | Diff live config against file config |
| `kubectl debug` | Create a debug container for a pod |
| `kubectl patch` | Update resource fields inline |
| `kubectl wait` | Wait for a specific resource condition |
| `kubectl annotate` | Add or update resource annotations |
| `kubectl auth can-i` | Check permission for an action |
| `kubectl replace` | Replace a resource from a file |
| `kubectl explain` | Show documentation for a resource field |
| `kubectl attach` | Attach to a running container |
| `kubectl proxy` | Run a proxy to the API server |
| `kubectl completion` | Generate shell auto-completion scripts |
| `kubectl kustomize` | Build a kustomization target |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice Kubernetes interactively** | [Open Terminal](https://technoscripts.com/cli/kubernetes/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/kubernetes-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type Kubernetes Commands](https://technoscripts.com/command-playground/typing-practice/kubernetes/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
