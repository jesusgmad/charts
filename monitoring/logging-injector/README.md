# Logging Sidecar Injector Chart

Deploy [mutating webook](https://kubernetes.io/docs/reference/access-authn-authz/extensible-admission-controllers/) to inject rsyslog client sidecar into pods.

```
helm install logging-injector ./charts/monitoring/logging-injector
```

## TLS Certificates

Mutation