This fork of [FiloSottile/yubikey-agent](https://github.com/FiloSottile/yubikey-agent)
adds the ability to retrieve the generated management key as defined in
[this PR](https://github.com/FiloSottile/yubikey-agent/pull/53).

```bash
nix build
result/bin/yubikey-agent  -get-management-key
```
