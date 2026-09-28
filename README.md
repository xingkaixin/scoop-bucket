# Scoop bucket

Scoop manifests maintained by xingkaixin.

```powershell
scoop bucket add xingkaixin https://github.com/xingkaixin/scoop-bucket
scoop install xingkaixin/codesesh
scoop update codesesh
scoop uninstall codesesh
```

CodeSesh supports Windows x64. No Node.js installation is required.
Run `codesesh` after installing. Stop any running CodeSesh process before upgrading, then restart it.

CodeSesh releases update `bucket/codesesh.json` from verified GitHub Release assets through the CodeSesh distribution workflow. Other tools can add their own manifests independently.
