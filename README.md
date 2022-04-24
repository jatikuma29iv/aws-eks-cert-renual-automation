# aws-eks-cert-renual-automation
project to
- install a letsencrypt cert to an existing cluster, and
- setup auto renual

## Existing setup
The cluster with following configuration will be provide by us

- AWS EKS cluster
- jetstack cert-manager
- Ingress Controller
  - AWS ELB
  - or Contour

## Requirement
In the existing AWS cluster
  - install letsencrypt certbot certifice
  - automate the renual process
  - add all the yamls to this project

References:
- https://www.digitalocean.com/community/tutorials/how-to-set-up-an-nginx-ingress-with-cert-manager-on-digitalocean-kubernetes
- https://aws.amazon.com/blogs/containers/securing-eks-ingress-contour-lets-encrypt-gitops/
- [How To Use Let’s Encrypt on Kubernetes to Automatically Generate Certs](https://runnable.com/blog/how-to-use-lets-encrypt-on-kubernetes)
  - github: https://github.com/thejsj/kubernetes-letsencrypt-demo/blob/master/letsencrypt.yml
