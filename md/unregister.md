> See also: [destroy-controller](/t/10113), [kill-controller](/t/10233), [register](/t/10160)

## Summary
Unregisters a Juju controller.

## Usage
```juju unregister [options] <controller name>```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--no-prompt` | false | Do not ask for confirmation |

## Examples

    juju unregister my-controller


## Details

Removes local connection information for the specified controller.  This
command does not destroy the controller.  In order to regain access to an
unregistered controller, it will need to be added again using the juju register
command.



---

