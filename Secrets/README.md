### How to refer to secrets in your code

```yaml
env: 
  - name: SECRET_NAME
    valueFrom:
      secretKeyRef:
        name: secret-name
        key: secret-key
```