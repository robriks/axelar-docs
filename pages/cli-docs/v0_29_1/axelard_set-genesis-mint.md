## axelard set-genesis-mint

Set the genesis parameters for the mint module

```
axelard set-genesis-mint [flags]
```

### Options

```
      --blocks-per-year uint               Expected number of blocks per year
      --goal-bonded string                 The target ratio of bonded stake to total supply
  -h, --help                               help for set-genesis-mint
      --inflation-max string               Maximum inflation rate
      --inflation-max-rate-change string   Maximum inflation rate change
      --inflation-min string               Minimum inflation rate
      --mint-denom string                  Denomination of minted tokens
```

### Options inherited from parent commands

```
      --home string         directory for config and data (default "$HOME/.axelar")
      --log_format string   The logging format (json|plain) (default "plain")
      --log_level string    The logging level (trace|debug|info|warn|error|fatal|panic) (default "info")
      --output string       Output format (text|json) (default "text")
      --trace               print out full stack trace on errors
```

### SEE ALSO

- [axelard](/cli-docs/v0_29_1/axelard) - Axelar App