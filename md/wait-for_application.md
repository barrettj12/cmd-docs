
## Summary
Wait for an application to reach a specified state.

## Usage
```juju wait-for application [options] [<name>]```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--B`, `--no-browser-login` | false | Do not use web browser for authentication |
| `--m`, `--model` |  | Model to operate in. Accepts [&lt;controller name&gt;:]&lt;model name&gt;&#x7c;&lt;model UUID&gt; |
| `--query` | life=="alive" &amp;&amp; status=="active" | query the goal state |
| `--summary` | true | output a summary of the application query on exit |
| `--timeout` | 10m0s | how long to wait, before timing out |

## Details

Waits for an application to reach a specified state.
arguments:
name
   application name identifier
options:
--query (= 'life=="alive" &amp;&amp; status=="active"')
   query represents the sought state of the specified application


---

