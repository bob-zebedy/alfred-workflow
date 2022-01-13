# alfred-workflow

## Keychain TOTP

```shell
brew install oath-toolkit
```

- 新增 TOTP
```shell
totp+ <service-name:required> <secret-token:required> <times-step:optional:30>
```
- 查询 TOTP
```shell
totp <service-name:required>
```