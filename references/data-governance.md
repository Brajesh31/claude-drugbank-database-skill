# DrugBank Data Governance

## Before use
- Verify the current license and permitted purpose.
- Confirm whether local storage, derived datasets, screenshots, or redistribution are allowed.
- Record the dataset release/version and access date.
- Use approved API or download mechanisms only.

## Provenance
For each extracted field retain:
- DrugBank identifier;
- source record type;
- original field name and value;
- unit and controlled vocabulary where supplied;
- dataset version;
- extraction timestamp;
- transformation applied.

## Data quality
- Treat missing, unknown, and not-applicable as different states.
- Do not silently merge records based on display name alone.
- Prefer stable identifiers and document any mapping table.
- Check whether a field is current, historical, curated, or predicted.

## Clinical boundary
Database entries are research information, not individualized medical advice. Interaction, indication, target, and pharmacokinetic records require context and qualified interpretation.
