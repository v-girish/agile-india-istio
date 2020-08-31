# Istio Demos for Service Mesh talk in Agile India 2019 Workshop
Talk link [here](https://www.youtube.com/watch?v=wQI0QGZ9xfU):


You can find the corresponding slides at this link:
```
https://docs.google.com/presentation/d/1PC_eRPgLh5MrUDe4UAog88L9jNl8RfgevCpLlldLHrI/edit?usp=sharing
```

## Set up Istio in K8s cluster
Run the setup_istio.sh script to install istio components using helm
```
$ ./setup_istio.sh
```

## Book Info Application
This is the default bookinfo application that is provided by istio folks. This application is just used for demo purposes.
To install bookinfo app in k8s cluster run the following command
```console
$ kubectl apply -f bookinfo/
```

## Request Routing
TO apply any traffic routing rule, run the following command
```
$ kubectl apply -f request_routing/<rule>.yaml
``` 
