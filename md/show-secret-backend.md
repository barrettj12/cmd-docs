> See also: [add-secret-backend](/t/10062), [secret-backends](/t/10149), [remove-secret-backend](/t/10194), [update-secret-backend](/t/10176)

## Summary
Displays the specified secret backend.

## Usage
```juju show-secret-backend [options] <backend-name>```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--c`, `--controller` |  | Controller to operate in |
| `--format` | yaml | Specify output format (json&#x7c;yaml) |
| `--o`, `--output` |  | Specify an output file |
| `--reveal` | false | Include sensitive backend config content |

## Examples

    juju show-secret-backend myvault
    juju secret-backends myvault --reveal


## Details

Displays the specified secret backend.


---

