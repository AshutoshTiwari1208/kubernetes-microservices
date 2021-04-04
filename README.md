# HOW TO RUN THIS APP IN k8's CLUSTER

Routes Available:

=> get /story

=> post /story
    body: {
        "text": "Store this thought"
    }

## Follow the steps 👇

1. Download Minikube & kubectl

2. Goto kubernetes folder and apply all files

```kubectl apply -f <filename.yaml>```

5. ```minikube service frontend-service```

> Now, you can access the application! 😃