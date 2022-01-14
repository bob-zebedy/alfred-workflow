# alfred-workflow

## Keychain OTP

```shell
brew install oath-toolkit
```

- 新增 OTP
```shell
otp+ <service-name:required> <secret-token:required> <mode:optional:[SHA1(default)|SHA256|SHA512]> <times-step:optional[30(default)]>
```
- 查询 OTP
```shell
otp <service-name:required>
```