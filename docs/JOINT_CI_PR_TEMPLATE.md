# Joint CI PR body template (Synapse)

```
CI_MODE=joint
JOINT_WAIT=true
JOINT_CI_ID=exp-YYYYMMDD-NNN
DEPENDS_ON: zhekui-hub/joint-ci-driver@<branch>
```

- `joint-ci` = Arsenal public tests only
- `synapse-precheck` / `synapse-independent-ci` = this repo
