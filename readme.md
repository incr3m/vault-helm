based on this helm chart - https://github.com/helm/charts/tree/master/incubator/vault

helm install --name vault --namespace vault --version 0.13.1 --values values.yaml incubator/vault
helm upgrade --install vault --namespace vault --version 0.13.1 --values values.yaml incubator/vault