# Firecracker (firecracker)
Firecracker is an open source virtual machine monitor (VMM) built by Amazon Web Services that uses KVM to create and manage lightweight microVMs. Designed for serverless computing and container workloads, it provides the security and isolation of traditional VMs with the speed and resource efficiency of containers. Firecracker exposes a RESTful management API over a Unix Domain Socket, specified in OpenAPI (Swagger 2.0).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/firecracker/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags:

 - AWS, Containers, MicroVMs, Open Source, Serverless, Virtualization, KVM

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-28

## APIs

### Firecracker API
The Firecracker management API is a RESTful public-facing API accessible through HTTP calls over a Unix Domain Socket, carrying JSON modeled data. It is used to configure and control microVMs, including boot source, drives, network interfaces, machine configuration, snapshots, and lifecycle actions. Firecracker powers AWS Lambda and AWS Fargate.

**Human URL:** [https://github.com/firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker)

**Base URL:** `http://localhost/` (over Unix Domain Socket)

#### Tags:

 - AWS, Containers, MicroVMs, Open Source, Serverless, Virtualization

#### Properties

- [Documentation](https://github.com/firecracker-microvm/firecracker/tree/main/docs)
- [Getting Started](https://github.com/firecracker-microvm/firecracker/blob/main/docs/getting-started.md)
- [API Requests](https://github.com/firecracker-microvm/firecracker/tree/main/docs/api_requests)
- [OpenAPI](openapi/firecracker-openapi-original.yaml)
- [Specification](https://github.com/firecracker-microvm/firecracker/blob/main/SPECIFICATION.md)
- [Design](https://github.com/firecracker-microvm/firecracker/blob/main/docs/design.md)

## Common Properties

- [Website](https://firecracker-microvm.github.io/)
- [GitHub Organization](https://github.com/firecracker-microvm)
- [GitHub Repository](https://github.com/firecracker-microvm/firecracker)
- [Documentation](https://github.com/firecracker-microvm/firecracker/tree/main/docs)
- [Getting Started](https://github.com/firecracker-microvm/firecracker/blob/main/docs/getting-started.md)
- [ChangeLog](https://github.com/firecracker-microvm/firecracker/blob/main/CHANGELOG.md)
- [FAQ](https://github.com/firecracker-microvm/firecracker/blob/main/FAQ.md)
- [Security](https://github.com/firecracker-microvm/firecracker/blob/main/SECURITY.md)
- [Blog](https://aws.amazon.com/blogs/opensource/tag/firecracker/)
- [Slack](https://join.slack.com/t/firecracker-microvm/shared_invite/zt-2tc0mfxpc-tU~HYAYSzLDl5XGGJU3YIg)
- [Email](mailto:firecracker-maintainers@amazon.com)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
