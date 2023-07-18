
## Summary
Update a resource for an application.

## Usage
```juju attach-resource [options] application name=file|OCI image```

### Options
| Flag | Default | Usage |
| --- | --- | --- |
| `--B`, `--no-browser-login` | false | Do not use web browser for authentication |
| `--m`, `--model` |  | Model to operate in. Accepts [&lt;controller name&gt;:]&lt;model name&gt;&#x7c;&lt;model UUID&gt; |

## Details

This command updates a resource for an application.

For file resources, it uploads a file from your local disk to the juju controller to be
streamed to the charm when "resource-get" is called by a hook.

For OCI image resources used by k8s applications, an OCI image or file path is specified.
A file is specified when a private OCI image is needed and the username/password used to
access the image is needed along with the image path.


---

