# Sonarqube

You must have the following services installed on your kubernetes cluster before creating a Sonarqube:

* cert-manager
* cluster-issuer
* ingress-nginx

Also, you must have a DNS record created for sonarqube.

---
**NOTE**

Instead of using a database inside kubernetes, you can use external databases like AWS RDS, GCP Cloud SQL... In that case, just skip `sonarqube-db.yaml` creation.

---
