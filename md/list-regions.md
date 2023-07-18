> See also: [add-cloud](/t/10162), [clouds](/t/10182), [show-cloud](/t/10215), [update-cloud](/t/10081), [update-public-clouds](/t/10115)
**Alias:** regions

## Summary
Lists regions for a given cloud.

## Usage
```juju list-regions [options] <cloud>```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--B`, `--no-browser-login` | false | Do not use web browser for authentication |
| `--c`, `--controller` |  | Controller to operate in |
| `--client` | false | Client operation |
| `--format` | tabular | Specify output format (json&#x7c;tabular&#x7c;yaml) |
| `--o`, `--output` |  | Specify an output file |

## Examples

    juju regions aws
    juju regions aws --controller mycontroller
    juju regions aws --client
    juju regions aws --client --controller mycontroller


## Details

List regions for a given cloud.

Use --controller option to list regions from the cloud from a controller.

Use --client option to list regions known locally on this client.


---

