# scoop-bucket

Scoop bucket for [vessel](https://github.com/spenceclark/Vessel).

```powershell
scoop bucket add spenceclark https://github.com/spenceclark/scoop-bucket
scoop install vessel
```

`bucket/vessel.json` is bumped automatically by vessel's release workflow on
every tagged release. The `checkver`/`autoupdate` fields also let Scoop's own
`scoop update` bot pick up new releases without waiting on that workflow.
