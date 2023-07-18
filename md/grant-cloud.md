> See also: [revoke-cloud](/t/10104), [add-user](/t/10193)

## Summary
Grants access level to a Juju user for a cloud.

## Usage
```juju grant-cloud [options] <user name> <permission> <cloud name> ...```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--B`, `--no-browser-login` | false | Do not use web browser for authentication |
| `--c`, `--controller` |  | Controller to operate in |

## Examples

Grant user 'joe' 'add-model' access to cloud 'fluffy':

    juju grant-cloud joe add-model fluffy


## Details
Valid access levels are:
    admin
    add-model

---

