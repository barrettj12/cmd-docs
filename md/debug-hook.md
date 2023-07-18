**Alias:** debug-hooks

## Summary
Launch a tmux session to debug hooks and/or actions.

## Usage
```juju debug-hooks [options] <unit name> [hook or action names]```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--container` |  | the container name of the target pod |
| `--m`, `--model` |  | Model to operate in. Accepts [&lt;controller name&gt;:]&lt;model name&gt;&#x7c;&lt;model UUID&gt; |
| `--no-host-key-checks` | false | Skip host key checking (INSECURE) |
| `--proxy` | false | Proxy through the API server |
| `--pty` | &lt;auto&gt; | Enable pseudo-tty allocation |
| `--remote` | false | Target on the workload or operator pod (k8s-only) |

## Details

Interactively debug hooks or actions remotely on an application unit.

Valid unit identifiers are:
  a standard unit ID, such as mysql/0 or;
  leader syntax of the form &lt;application&gt;/leader, such as mysql/leader.

See the "juju help ssh" for information about SSH related options
accepted by the debug-hooks command.


---

