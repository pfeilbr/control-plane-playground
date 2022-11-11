# control-plane-playground

learn [Control Plane](https://controlplane.com/)

## General

- multi-cloud (aws, azure, gcp)
- costs - compute, memory and egress are passed along to customer
- move off of platfrom team.
- checking latency 10xs per sec
- health check - multi-cloud for everything.  resilient.
- dns is 2 major providers - rt 53, constellex
- graphana under the covers
- control plane can use oidc connect for aws identity ([Creating OpenID Connect (OIDC) identity providers](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_providers_create_oidc.html))
- reduced complexity for eng teams

## Concepts

- Org - strictly isolated bounded context that encapsulates all the resources managed by Control Plane
- Global Virtual Cloud (GVC) - defines a set of cloud providers and their locations.
- Workloads - you specify a container image.  this is the unit of deployment.
- Policy - governs resource access within an org to a set of principals. It enables fine-grained authorization rules to define the minimum amount of permissions required when accessing resources of the platform.
- Principal Types
  - supports 4 principal types.
    - Users
    - Service Accounts
    - Groups
    - Identity
- Accessing Cloud Resources

## Demo



```sh
# cli usage only for the deployment of resources


```

## Questions

- recommendation for secrets storage (api keys, db creds, etc.)
- is there an iac solution for provisioning workload?  what is used for "repeatability"

## Resources

- [Control Plane](https://controlplane.com/)
- <https://docs.controlplane.com/>