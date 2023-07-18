
## Summary
Wait for an entity to reach a specified state.

## Usage
```juju wait-for [options] <command> ...```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--description` | false | Show short description of plugin, if any |
| `--h`, `--help` | false | Show help on a command or other topic. |

## Details
Waits for a specified model, machine, application or unit to reach a state
defined by the supplied query.

Examples:
	juju wait-for unit mysql/0
	juju wait-for application mysql --query='name=="mysql" &amp;&amp; (status=="active" &#x7c;&#x7c; status=="idle")'

## Subcommands
- [application](/t/12345)
- [machine](/t/12346)
- [model](/t/12347)
- [unit](/t/12348)

---

