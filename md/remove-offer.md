> See also: [find-offers](/t/10097), [offer](/t/10080)

## Summary
Removes one or more offers specified by their URL.

## Usage
```juju remove-offer [options] <offer-url> ...```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--B`, `--no-browser-login` | false | Do not use web browser for authentication |
| `--c`, `--controller` |  | Controller to operate in |
| `--force` | false | remove the offer as well as any relations to the offer |
| `--y`, `--yes` | false | Do not prompt for confirmation |

## Examples

    juju remove-offer prod.model/hosted-mysql
    juju remove-offer prod.model/hosted-mysql --force
    juju remove-offer hosted-mysql


## Details

Remove one or more application offers.

If the --force option is specified, any existing relations to the
offer will also be removed.

Offers to remove are normally specified by their URL.
It's also possible to specify just the offer name, in which case
the offer is considered to reside in the current model.


---

