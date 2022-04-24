# aws-eks-cert-renual-automation

## PROJECTS REQUIREMENTS
In the existing `AWS EKS Cluster`
- install `let's encrypt` `certbot` certificate
- automate the renewal process
- add all the `yamls` to this project

## EXISTING SETUP
The cluster with following configuration will be provide by us
- `AWS EKS Cluster`
- `jetstack cert-manager`
- `Ingress Controller`
  - `AWS ELB`
  - or `Contour`

## REFERENCES
- https://www.digitalocean.com/community/tutorials/how-to-set-up-an-nginx-ingress-with-cert-manager-on-digitalocean-kubernetes
- https://aws.amazon.com/blogs/containers/securing-eks-ingress-contour-lets-encrypt-gitops/
- [How To Use Let’s Encrypt on Kubernetes to Automatically Generate Certs](https://runnable.com/blog/how-to-use-lets-encrypt-on-kubernetes)
  - github: https://github.com/thejsj/kubernetes-letsencrypt-demo/blob/master/letsencrypt.yml
