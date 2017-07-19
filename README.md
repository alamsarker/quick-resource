

## Helm

1. `helm package coverage`
2. `helm install --name coverage-qa coverage-0.0.2.tgz -f values.yaml`
3. `helm upgrade coverage coverage-0.0.2.tgz -f values.yaml`
4. `helm delete --purge coverage-qa`
