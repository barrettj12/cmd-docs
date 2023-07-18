> See also: [add-secret-backend](/t/10062), [secret-backends](/t/10149), [show-secret-backend](/t/10059), [update-secret-backend](/t/10176)

## Summary
Removes a secret backend from the controller.

## Usage
```juju remove-secret-backend [options] <backend-name>```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--c`, `--controller` |  | Controller to operate in |
| `--force` | false | force removal even if the backend stores in-use secrets |

## Examples

    juju remove-secret-backend myvault
    juju remove-secret-backend myvault --force


## Details

Removes a secret backend, used for storing secret content.
If the backend is being used to store secrets currently in use,
the --force option can be supplied to force the removal, but be
warned, this will affect charms which use those secrets.


---

