> See also: [add-space](/t/10117), [spaces](/t/10236), [reload-spaces](/t/10063), [rename-space](/t/10135), [remove-space](/t/10084)

## Summary
Shows information about the network space.

## Usage
```juju show-space [options] <name>```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--B`, `--no-browser-login` | false | Do not use web browser for authentication |
| `--format` | yaml | Specify output format (json&#x7c;yaml) |
| `--m`, `--model` |  | Model to operate in. Accepts [&lt;controller name&gt;:]&lt;model name&gt;&#x7c;&lt;model UUID&gt; |
| `--o`, `--output` |  | Specify an output file |

## Examples

Show a space by name:

	juju show-space alpha


## Details
Displays extended information about a given space. 
Output includes the space subnets, applications with bindings to the space,
and a count of machines connected to the space.

---

