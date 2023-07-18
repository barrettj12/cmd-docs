> See also: [unregister](/t/10165), [revoke](/t/10077), [show-user](/t/10212), [users](/t/10175), [disable-user](/t/10198), [enable-user](/t/10241), [change-user-password](/t/10118)

## Summary
Deletes a Juju user from a controller.

## Usage
```juju remove-user [options] <user name>```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--B`, `--no-browser-login` | false | Do not use web browser for authentication |
| `--c`, `--controller` |  | Controller to operate in |
| `--y`, `--yes` | false | Confirm deletion of the user |

## Examples

    juju remove-user bob
    juju remove-user bob --yes


## Details
This removes a user permanently.

By default, the controller is the current controller.



---

