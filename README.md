# istio

#### Comandos básicos

###### Mostrando as dashboard
Ele retireciona para a porta do meu host e consigo acessar via http://localhost:porta da dashboard.
```
istioctl dashboard kiali ou grafna ou jaeger
```

###### Habilitando e vinculando o istio ao seu namespace no microk8s

```
microk8s.enable istio
microk8s.kubectl label namespace default istio-injection=enabled
``` 
