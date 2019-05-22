# aks-playground


- Create docker-registry secret:


``` bash
kubectl create secret docker-registry cnguerlainclientelingallallacr --docker-server=REGISTRY_NAME.azurecr.io \
--docker-username=USERNAME \
--docker-password=PASSWORD \
--docker-email=ANY_VALID_EMAIL
```