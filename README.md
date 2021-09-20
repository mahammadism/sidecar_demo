# sidecar_demo
# Sending Ngninx logs to S3 bucket using Side car conept.
# sidecar-deployment.yaml file will create a nginx container which logs can be stored in /var/log/nginx mount path which is same for Side car container also.
# So what ever the logs can be stored in /var/log/nginx mount path those can be reflected and can be accessed from Side car container.
