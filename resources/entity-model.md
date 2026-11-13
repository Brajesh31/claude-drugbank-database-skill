# Drug Data Entity Model

This is a neutral working model for organizing authorized records. It is not a replacement for the official DrugBank schema.

## Suggested entities
- Drug: stable source identifier, preferred name, synonyms, status.
- Product: product identifier, brand, strength, dosage form, jurisdiction.
- Target: source identifier, name, organism, target type.
- Interaction: two or more drug references, source description, evidence/provenance.
- Pathway: pathway identifier, name, related targets or compounds.
- SourceRecord: dataset version, source field, extraction timestamp, license context.

## Relationship cautions
- A brand product is not the same entity as an active ingredient.
- A target relationship is not proof of clinical efficacy.
- Interaction records may depend on evidence level and context.
- Preserve source identifiers even when mapping to external ontologies.
