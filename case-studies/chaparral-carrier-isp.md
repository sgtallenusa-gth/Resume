# Case Study: Chaparral Carrier ISP Architecture and Transformation

## Context

Chaparral operated a regional fixed wireless ISP serving more than 12,000 subscribers across 30+ tower sites, supported by three datacenters and a mix of MikroTik, Cambium, Tarana, Proxmox, Ceph, and BGP-based internet edge infrastructure.

## Infrastructure Scale

- 12,000+ MikroTik CPE devices, primarily RB4011, hAP ac3, and hAP ax3.
- 30 tower sites.
- Typical tower architecture: 2 CCR2216 routers, 1 CRS518, 1 CRS328, Cambium PMP450 sectors, and Tarana 5/6 GHz sectors.
- Three functional datacenters: one primary and two offsite redundant sites.
- Core datacenter: seven-node Proxmox cluster with Ceph across a 100 Gbps backbone.
- Internet edge: 100 Gbps primary BGP circuit and two 20 Gbps backup BGP circuits.

## Leadership Challenge

At its height, the organization had approximately 100 employees, including architecture engineers, mid-level network engineers, Tier 1 technicians, customer service representatives, inside plant and outside plant crews, tower crews, and installation teams.

As staffing levels decreased, the organization needed to maintain service quality and stability with a smaller team footprint.

## Transformation

I responded by implementing automation-first operations, AI-assisted monitoring workflows, documentation standards, provisioning tooling, and training programs that allowed the organization to continue operating at scale.

## Results

- Supported carrier-scale infrastructure serving 12,000+ subscribers.
- Led network operations, infrastructure architecture, and team development.
- Trained and mentored NOC and customer service staff to build the skills required for daily operations.
- Maintained focus on resilient, repeatable, documented infrastructure.
