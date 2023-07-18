
## Summary
Wait for a model to reach a specified state.

## Usage
```juju wait-for model [options] [<name>]```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--B`, `--no-browser-login` | false | Do not use web browser for authentication |
| `--m`, `--model` |  | Model to operate in. Accepts [&lt;controller name&gt;:]&lt;model name&gt;&#x7c;&lt;model UUID&gt; |
| `--query` | life=="alive" &amp;&amp; status=="available" | query the goal state |
| `--summary` | true | output a summary of the application query on exit |
| `--timeout` | 10m0s | how long to wait, before timing out |

## Details

Waits for a model to reach a specified state.

arguments:
name
   model name identifier

options:
--query (= 'life=="alive" &amp;&amp; status=="available"')
   query represents the sought state of the specified model


---

