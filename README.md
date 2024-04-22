# helm-wordpress    go to this links for all details "https://jhooq.com/helm-chart-wordpress-installation/"
Setup Wordpress using Helm Chart on Kubernetes using GKE

1- CREATE A CLUSTER ON GCP AND CONNECT TO IT 
2- CHECK THE NEW NODES USING kubectl get nodes
3- Add '/bitnami/wordpress' wordpress repo to your helm installation by:
       -search it using the cmd line "helm search hub wordpress"
       - look thru the outcome for https://hub.helm.sh/charts/bitnami/wordpress. "In case if the URL is too long to see then you can put --max-col-width=0, so that you can view the complete URL" like this "helm search hub wordpress  --max-col-width=0"

       - add bitnami- wordpress to your repo "helm repo add bitnami https://charts.bitnami.com/bitnami"
       - Check Wordpress Version "helm search repo wordpress --versions"
       - 




