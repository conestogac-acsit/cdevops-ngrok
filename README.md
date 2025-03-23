# cdevops-ngrok

k8s ngrok ingress

TLDR;

1. have a look at the `ingress.yaml` file to get your service and it's url correct
2. run the `up.yaml` playbook with API_KEY and AUTHTOKEN

```bash
ansible-playbook -e "NGROK_AUTHTOKEN=************************************ NGROK_API_KEY=***************************************" up.yaml
```

from [this article](https://blog.techiescamp.com/using-ngrok-with-kubernetes/)
