Overview
========

This bundle will deploy [Landscape On-Premises](https://landscape.canonical.com/landscape-features).
There are three slightly different versions of this bundle, explained below.

Dense Deployment - MAAS
=======================
`landscape-dense-maas` - For MAAS where LXDs can be addressed externally, you
can deploy to a single machine while at the same time making the service
scalable in the future.

Dense Deployment - Other
========================
`landscape-dense` - For other machine providers where LXD containers do not get
externally routable IP addresses. This will deploy the frontend on the machine
itself, and the remaining backend services in containers. This approach is not
currently scalable to another physical system but conserves resources.

Scalable Deployment
===================
`landscape-scalable` - A fully scalable multi-machine deployment.
