# action-gtin-registry — governed product-identity registry

**Repository**: `cloud-itonami/action-gtin-registry`

Operational registry actor for GTIN, JAN, UPC, and EAN trade-item identities.
The reusable identifier/catalog substrate remains `cloud-itonami/gtin`; this
repository owns governed registration, normalization, quality review, and
publication workflows.

The historical GTIN DID, `gtin.etzhayyim.com`, and `com.etzhayyim.*` protocol
namespaces remain compatibility identities. Run `kbb run_tests.cljk` to verify
the actor contracts.
