

## Helm

`helm package coverage`
`helm install --name coverage-qa coverage-0.0.2.tgz -f values.yaml`
`helm upgrade coverage coverage-0.0.2.tgz -f values.yaml`
`helm delete --purge coverage-qa`
