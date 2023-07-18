> See also: [secret-backends](/t/10149), [remove-secret-backend](/t/10194), [show-secret-backend](/t/10059), [update-secret-backend](/t/10176)

## Summary
Add a new secret backend to the controller.

## Usage
```juju add-secret-backend [options] <backend-name> <backend-type>```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--c`, `--controller` |  | Controller to operate in |
| `--config` |  | path to yaml-formatted configuration file |
| `--import-id` |  | add the backend with the specified id |

## Examples

    juju add-secret-backend myvault vault --config /path/to/cfg.yaml
    juju add-secret-backend myvault vault token-rotate=10m --config /path/to/cfg.yaml
    juju add-secret-backend myvault vault endpoint=https://vault.io:8200 token=s.1wshwhw


## Details

Adds a new secret backend for storing secret content.

You must specify a name for the backend and its type,
followed by any necessary backend specific config values.
Config may be specified as key values ot read from a file.
Any key values override file content if both are specified.

To rotate the backend access credential/token (if specified), use
the "token-rotate" config and supply a duration.



---

