---
title: "Amazon EKS now supports customer-routed control plane egress"
url: "https://aws.amazon.com/about-aws/whats-new/2026/06/amazon-eks-customer-routed-control-plane-egress"
date: "2026-06-18"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
EKS now supports customer-routed control plane egress, routing Kubernetes API server traffic (admission webhook callbacks, OIDC provider lookups, and aggregate API server requests) through user VPCs. Organizations with data perimeter requirements can reach private OIDC providers and webhooks at no cost by setting controlPlaneEgressMode to CUSTOMER_ROUTED.
