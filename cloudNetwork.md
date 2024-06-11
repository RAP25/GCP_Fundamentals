| Concept | Google Cloud | AWS|
|---------|--------------|-------|
| Cluster of data centers and services | Region | Region | 
| Abstracted data center | Zone | Availability Zone |
| Edge caching | PoPs (Multiple services) | PoPs (Multiple services) |


## Security
cloud.google.com/security/security-design
### Hardware infrasrtucture layer
* h/w design and provenance
* secure boot stack
* premises security

### Service deployment layer
* Encryption of inter-service communication

### User identtiy layer
* user identity

### Storage services layer
* encryption at rest

### Internet communication layer
* Google Frond End GFE
* Denial of Serice protection

### Operational security layer
* Intrusion detection
* reducing insider risk
* employee Universal Second Factor U2F use
* Software developemnet practices

## Open source ecosystems

## Pricing and Billing
- per-second billing - GKE; DataProc; AppEngine 
- Compute Engine - discount for every incremental use
- Custom virtual machines - tailored pricing
- online pricing calculator cloud.google.com/products/calculator
- **Budgets** at billing account level or porject level
- Create **alerts** on budge limits
- Reports : visual tool to monitor consumption and cost
- Quotas
    Rate quota: Resets after a specific time
    Allocation quota: Governs number of resources
