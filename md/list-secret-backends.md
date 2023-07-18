> See also: [add-secret-backend](/t/10062), [remove-secret-backend](/t/10194), [show-secret-backend](/t/10059), [update-secret-backend](/t/10176)
**Alias:** secret-backends

## Summary
Lists secret backends available in the controller.

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--c`, `--controller` |  | Controller to operate in |
| `--format` | tabular | Specify output format (json&#x7c;tabular&#x7c;yaml) |
| `--o`, `--output` |  | Specify an output file |
| `--reveal` | false | Include sensitive backend config content |

## Examples

    juju secret-backends
    juju secret-backends --format yaml


## Details

Displays the secret backends available for storing secret content.


---

