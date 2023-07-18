> See also: [register](/t/10160), [grant](/t/10196), [users](/t/10175), [show-user](/t/10212), [disable-user](/t/10198), [enable-user](/t/10241), [change-user-password](/t/10118), [remove-user](/t/10130)

## Summary
Adds a Juju user to a controller.

## Usage
```juju add-user [options] <user name> [<display name>]```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--B`, `--no-browser-login` | false | Do not use web browser for authentication |
| `--c`, `--controller` |  | Controller to operate in |

## Examples

    juju add-user bob
    juju add-user --controller mycontroller bob


## Details

The user's details are stored within the controller and will be removed when
the controller is destroyed.

A user unique registration string will be printed. This registration string 
must be used by the newly added user as supplied to complete the registration
process.

Some machine providers will require the user to be in possession of certain
credentials in order to create a model.



---

