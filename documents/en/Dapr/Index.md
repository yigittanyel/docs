# ABP Dapr Integration v3
Dapr (Distributed Application Runtime) provides APIs that simplify microservice connectivity. It is an open source project that is mainly backed by Microsoft. It is also a CNCF (Cloud Native Computing Foundation) project and trusted by the community.

## ABP Dapr Integration Packages
- Volo.Abp.Dapr: The main Dapr integration package. All other packages depend on this package.
- Volo.Abp.Http.Client.Dapr: Integration package for ABP's dynamic and static C# API Client Proxies systems with Dapr's service invocation building block.
- Volo.Abp.EventBus.Dapr: Implements ABP's distributed event bus with Dapr's publish & subscribe building block. With this package, you can send events, but can not receive.