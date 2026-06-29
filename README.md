# AGID Central Africa Index

AGID Central Africa index for Africa country and territory repository coordination.

## Status

- Owner: `dawnportinfo-design`
- Repository: `agid-africa-central-africa-index`
- Stage: `wave-0-index`
- Data readiness: `index-ready`
- Privacy: no raw personal address, recipient, precise private coordinate, witness, or private-key material.

## Scope

This repository is an AGID coordination index. It stores repository pointers,
safe source policy, postal status, quality gates, conformance status, and
special-region display policy for Africa address infrastructure.

It does not store private delivery addresses, recipient records, precise private
coordinates, witness material, private keys, large GIS extracts, map tiles,
search indexes, or humanitarian datasets containing personal data.

## Related Repositories

- `agid-country-cd` - DR Congo (CD)
- `agid-country-ao` - Angola (AO)
- `agid-country-cm` - Cameroon (CM)
- `agid-country-td` - Chad (TD)
- `agid-country-cf` - Central African Republic (CF)
- `agid-country-cg` - Congo (CG)
- `agid-country-ga` - Gabon (GA)
- `agid-country-gq` - Equatorial Guinea (GQ)
- `agid-country-st` - Sao Tome and Principe (ST)

## Data Boundary

GitHub may contain synthetic fixtures, rules, manifests, source notes, postal
status, and quality gate metadata. Large geography, humanitarian datasets,
building polygons, OSM/Overture extracts, routing networks, and generated
caches must stay in external content-addressed packs.

## Postal-Weak And No-Postal Policy

Many Africa country packs require AGID-first delivery, postal-equivalent zones,
informal settlement handling, rural and nomadic addressing, island and desert
delivery profiles, and humanitarian delivery workflows. These modes must be
declared as technical address infrastructure, not as raw address publication.

## Special Region Policy

AGID repository placement is a technical address-data organization rule. It does
not imply sovereignty, recognition, or territorial ownership. Disputed, de
facto, humanitarian, or special regions must carry explicit source, license,
canonical region, and display policy before data publication.

## Validation

The repository includes JSON manifests and a lightweight GitHub Actions workflow
that validates JSON files. Public release content must pass AGID no-raw-address
review before data publication.
