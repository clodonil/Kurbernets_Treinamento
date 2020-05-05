



```
$ minikube start 
```

Habilitando o Dashboard

```
$ minikube dashboard --url
```

Se não tiver utilizando o kubernetes no mesmo computador que esta trabalhando e precisar criar um redirecionamento de portas.

```
$ kubectl proxy --address='0.0.0.0' --disable-filter=true
```