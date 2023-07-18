> See also: [info](/t/10103), [find](/t/10187)

## Summary
Locates and then downloads a CharmHub charm.

## Usage
```juju download [options] [options] <charm>```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--arch` | all | specify an arch &lt;all&#x7c;amd64&#x7c;arm64&#x7c;ppc64el&#x7c;riscv64&#x7c;s390x&gt; |
| `--base` |  | specify a base |
| `--channel` |  | specify a channel to use instead of the default release |
| `--charmhub-url` | https://api.charmhub.io | specify the Charmhub URL for querying the store |
| `--filepath` |  | filepath location of the charm to download to |
| `--no-progress` | false | disable the progress bar |
| `--series` | all | specify a series. DEPRECATED use --base |

## Examples

    juju download postgresql
    juju download postgresql --no-progress - > postgresql.charm


## Details

Download a charm to the current directory from the CharmHub store
by a specified name. Downloading for a specific base can be done via
--base. --base can be specified using the OS name and the version of
the OS, separated by @. For example, --base ubuntu@22.04.

Adding a hyphen as the second argument allows the download to be piped
to stdout.


---

