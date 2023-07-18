> See also: [add-user](/t/10193), [register](/t/10160), [users](/t/10175)

## Summary
Show information about a user.

## Usage
```juju show-user [options] [<user name>]```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--c`, `--controller` |  | Controller to operate in |
| `--exact-time` | false | Use full timestamp for connection times |
| `--format` | yaml | Specify output format (json&#x7c;yaml) |
| `--o`, `--output` |  | Specify an output file |

## Examples

    juju show-user
    juju show-user jsmith
    juju show-user --format json
    juju show-user --format yaml


## Details
By default, the YAML format is used and the user name is the current
user.


---

