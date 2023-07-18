> See also: [add-cloud](/t/10162), [update-cloud](/t/10081), [clouds](/t/10182)

## Summary
Removes a cloud from Juju.

## Usage
```juju remove-cloud [options] <cloud name>```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--B`, `--no-browser-login` | false | Do not use web browser for authentication |
| `--c`, `--controller` |  | Controller to operate in |
| `--client` | false | Client operation |

## Examples

    juju remove-cloud mycloud
    juju remove-cloud mycloud --client
    juju remove-cloud mycloud --controller mycontroller


## Details

Remove a cloud from Juju.

If --controller is used, also remove the cloud from the specified controller,
if it is not in use.

If --client is specified, Juju removes the cloud from this client.



---

