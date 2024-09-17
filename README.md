# amp-example-sway

This is an example of using Sway with AMP.

## Preparing

* Install AMP client: https://docs.amphitheatre.app/installation/cli/

* Update configuration in `.amp.toml`

```toml
[build.env]
BP_ENABLE_FORC_DEPLOY = "true"
BP_HOME = "/layers/amp-buildpacks_forc/forc-amd64/fuel"
```

## Running

```bash
amp run
```

## Credits

Sample codes copied from https://docs.fuel.network/guides/contract-quickstart/
