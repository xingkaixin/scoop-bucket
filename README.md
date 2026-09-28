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

## Agent Dump

After adding the bucket above:

```powershell
scoop install xingkaixin/agent-dump
scoop update agent-dump
scoop uninstall agent-dump
```

Agent Dump supports Windows x64 and installs a native CLI without Python or Node.js. Run `agent-dump --help` after installing. Its release workflow maintains `bucket/agent-dump.json` independently.
