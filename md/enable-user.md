> See also: [users](/t/10175), [disable-user](/t/10198), [login](/t/10157)

## Summary
Re-enables a previously disabled Juju user.

## Usage
```juju enable-user [options] <user name>```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--B`, `--no-browser-login` | false | Do not use web browser for authentication |
| `--c`, `--controller` |  | Controller to operate in |

## Examples

    juju enable-user bob


## Details
An enabled Juju user is one that can log in to a controller.


---

