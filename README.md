# go-dag

Directed acyclic graph (DAG) implementation in Go.

As indicated by the Sourcegraph team:

> The `dag` package from [terraform/hashicorp] is one of the most well maintained and tested DAG implementations in Go, and [many projects depend on it](https://sourcegraph.com/search?q=context:global+lang:Go+%22github.com/hashicorp/terraform/dag%22&patternType=standard&sm=1&groupBy=repo).
> However, it was [made internal](https://github.com/hashicorp/terraform/commit/70eebe3521d2f1ffcb5c12b75e90f1b82db94551).
> Additionally, upstream package contains a lot of extra dependencies where most projects do not need.
> By forking it, we can import it as a standlone package and introduce custom changes to make it more generic.

This is a fork of a fork.

The original source code came from the Terraform library, but it was buried in an internal folder.

Sourcegraph forked it and made it public, but they utilize a library that is not public in the implementation.

The original source code is found in [github.com/terraform/hashicorp/internal/dag](https://github.com/hashicorp/terraform/tree/main/internal/dag).

## Usage

```sh
go get github.com/gdcorp-digitalcare/go-dag
```

[terraform/hashicorp]: https://github.com/hashicorp/terraform
