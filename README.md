# Local Kubernetes With Flux
This work was created for the following LinkedIn Article:
https://www.linkedin.com/pulse/local-kubernetes-using-flux-traefik-cert-manager-friends-dave-johnson-rn4mc/


A few things to note:
- 1. cert-manager is setup to bypass K8S DNS and use 8.8.8.8 and 1.1.1.1 for certificates
- 2. You will need to edit your host file to point DNS to localhost for any addresses you want to use so for instance I have "jenkins.systechs.com" as an entry in my hostfile pointed to 127.0.0.1
- 3. This is a work in progress please contribute and help out if you like this.