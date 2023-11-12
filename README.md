# SPOF

Single point of failure

Proof of concept using git repos on multiple hosting providers to safeguard against information suppression.

```bash
git remote add github.com git@github.com:spuder/spof.git
git remote add gitlab.com git@gitlab.com:owenspencer/spof.git
git remote add keybase.io keybase://private/spuder/spof
```

`git push --all`
