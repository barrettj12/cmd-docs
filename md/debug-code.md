
## Summary
Launch a tmux session to debug hooks and/or actions.

## Usage
```juju debug-code [options] <unit name> [hook or action names]```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--at` | all | interpreted by the charm for where you want to stop, defaults to 'all' |
| `--container` |  | the container name of the target pod |
| `--m`, `--model` |  | Model to operate in. Accepts [&lt;controller name&gt;:]&lt;model name&gt;&#x7c;&lt;model UUID&gt; |
| `--no-host-key-checks` | false | Skip host key checking (INSECURE) |
| `--proxy` | false | Proxy through the API server |
| `--pty` | &lt;auto&gt; | Enable pseudo-tty allocation |
| `--remote` | false | Target on the workload or operator pod (k8s-only) |

## Details

Interactively debug hooks and actions on a unit.

Valid unit identifiers are:
  a standard unit ID, such as mysql/0 or;
  leader syntax of the form &lt;application&gt;/leader, such as mysql/leader.

Similar to 'juju debug-hooks' but rather than dropping you into a shell prompt, 
it runs the hooks and sets the JUJU_DEBUG_AT environment variable. 
Charms that implement support for this should use it to set breakpoints based on the environment
variable.

See the "juju help ssh" for information about SSH related options
accepted by the debug-hooks command.


---

