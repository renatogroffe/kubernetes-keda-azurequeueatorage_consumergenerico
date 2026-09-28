# kubernetes-keda-azurequeueatorage_consumergenerico
Objetos para Deployment de um Worker Service (consumer genérico) no Kubernetes utilizando KEDA, Azure Queue Storage e um Worker criado com .NET10. Foi definido 1 exemplo para ScaledObject (com cooldownPeriod).

Aplicação utilizada nos testes: **https://github.com/renatogroffe/dotnet10-worker-azurequeuestorage_generic-consumer**

Imagem que serviu de base para este exemplo:

```text
renatogroffe/dotnet10-worker-azurequeuestorage-consumer:1
```

## Testes