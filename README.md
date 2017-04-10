# operatorkit

The operatorkit package implements an opinionated framework for developing Kubernetes operators. It can be used as a library
in golang. It is built on top of our [microkit](https://github.com/giantswarm/microkit) framework which provides base functionality like logging and error handling.

## Current Scope

The initial scope is intentionally small and will be expanded as we and the community gain more experience developing operators.

* Kubernetes clientset using [client-go](https://github.com/kubernetes/client-go) for accessing the K8s APIs.

## Future Scope

The future scope may include but is not limited to.

* Managing TPRs (Third Party Resources).
* Watches for TPRs.
* Reconciliation loops for managing TPOs (Third Party Objects).

## Contact

- Mailing list: [giantswarm](https://groups.google.com/forum/!forum/giantswarm)
- IRC: #[giantswarm](irc://irc.freenode.org:6667/#giantswarm) on freenode.org
- Bugs: [issues](https://github.com/giantswarm/cert-operator/issues)

## Contributing & Reporting Bugs

See [CONTRIBUTING](CONTRIBUTING.md) for details on submitting patches, the contribution workflow as well as reporting bugs.

## License

operatorkit is under the Apache 2.0 license. See the [LICENSE](LICENSE) file for details.

### credit
- https://golang.org
- https://github.com/kubernetes/kubernetes
- https://github.com/go-kit/kit
