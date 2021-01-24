# basic-auth-secret - helm chart

    2020 Ondrej Sika <ondrej@ondrejsika.com>
    https://github.com/ondrejsika/basic-auth-secret-helm

## Usage

Add repo

```
helm repo add ondrejsika https://helm.oxs.cz
```

Install

```
helm upgrade --install \
  <name> ondrejsika/basic-auth-secret \
  --set user=<user> \
  --set password=<password>
```

## Parameters

### Required

- `user`
- `password`
