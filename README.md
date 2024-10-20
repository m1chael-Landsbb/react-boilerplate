<img src="website/static/k8s_controller_logo.svg" height="125px"></img>


[![Build Status](https://github.com/controller-framework/controller-sdk/workflows/deploy/badge.svg)](https://github.com/controller-framework/controller-sdk/actions)
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

## Documentation

Documentation is available on the [Controller SDK website][sdk-docs].

## Overview

This project is a component of the [Controller Framework][cf-home], an
open source toolkit for managing Kubernetes native applications, called
Controllers, in an effective, automated, and scalable way. Read more in
the [introduction blog post][cf-blog].

[Controllers][controller-link] simplify management of complex stateful
applications on Kubernetes infrastructure. However developing a Controller today can
be challenging due to factors such as low-level API usage, boilerplate code generation,
and lack of modularity leading to code duplication.

The Controller SDK is a framework leveraging the
[runtime-controller][runtime-controller] library to simplify
controller development by providing:

- High level APIs and abstractions for intuitive operational logic implementation
- Scaffolding and code generation tools for rapid project initialization
- Extensions addressing common Controller implementation patterns

## Dependency and platform support

### Go version

Release binaries are compiled using the Go compiler version specified in the [developer guide][dev-guide-prereqs].
A Go Controller project's Go version is defined in its `go.mod` file.

[dev-guide-prereqs]:https://sdk.controller-framework.io/docs/contribution-guidelines/developer-guide#prerequisites

### Kubernetes versions

Supported Kubernetes versions for your Controller project or relevant binary can be determined
by consulting this [compatibility guide][k8s-compat].

[k8s-compat]:https://sdk.controller-framework.io/docs/overview#kubernetes-version-compatibility

### Platforms

The supported platforms for all binaries and images are documented in [these tables][platforms].

[platforms]:https://sdk.controller-framework.io/docs/overview#platform-support

## Community and how to get involved

- [Controller framework community][controller-framework-community]
- [Communication channels][controller-framework-communication]
- [Project meetings][controller-framework-meetings]

## How to contribute

Review the [contributor documentation][contribution-docs].

## License

Controller SDK is licensed under Apache 2.0. See the [LICENSE][license_file] file for details.

[runtime-controller]: https://github.com/kubernetes-libs/runtime-controller
[license_file]:./LICENSE
[cf-home]: https://github.com/controller-framework
[cf-blog]: https://www.cloudnative-blog.io/introducing-the-controller-framework
[controller-link]: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/
[sdk-docs]: https://sdk.controller-framework.io
[controller-framework-community]: https://github.com/controller-framework/community
[controller-framework-communication]: https://github.com/controller-framework/community#get-involved
[controller-framework-meetings]: https://github.com/controller-framework/community#meetings
[contribution-docs]: https://sdk.controller-framework.io/docs/contribution-guidelines/
