---
title: "pgo_df"
---
## pgo df

Display disk space for clusters

### Synopsis

Displays the disk status for PostgreSQL clusters. For example:

	pgo df mycluster
	pgo df all
	pgo df --selector=env=research

```
pgo df [flags]
```

### Options

```
  -h, --help              help for df
  -s, --selector string   The selector to use for cluster filtering.
```

### Options inherited from parent commands

```
      --apiserver-url string     The URL for the PostgreSQL Operator apiserver.
      --debug                    Enable debugging when true.
  -n, --namespace string         The namespace to use for pgo requests.
      --pgo-ca-cert string       The CA Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-cert string   The Client Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-key string    The Client Key file path for authenticating to the PostgreSQL Operator apiserver.
```

### SEE ALSO

* [pgo](/operatorcli/cli/pgo/)	 - The pgo command line interface.

###### Auto generated by spf13/cobra on 3-Jun-2019
