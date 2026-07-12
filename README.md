# AGET Framework Vocabulary

Published SKOS concepts from the [AGET framework](https://github.com/aget-framework/aget) — configuration and lifecycle management for CLI-based human-AI collaborative coding agents.

**Namespace**: `https://w3id.org/aget/vocab#` (persistent, [w3id.org](https://w3id.org)-indirected)

| Representation | File | Media type |
|----------------|------|-----------|
| SKOS Turtle | [vocab.ttl](vocab.ttl) | text/turtle |
| JSON-LD | [vocab.jsonld](vocab.jsonld) | application/ld+json |
| HTML | [index.html](index.html) | text/html |

Content negotiation happens at the w3id.org redirect layer (W3C swbp-vocab-pub Recipe 3, hash namespace): `Accept: text/turtle` → `vocab.ttl`; `Accept: application/ld+json` → `vocab.jsonld`; `Accept: text/html` → `index.html`; default (including `*/*` and empty Accept) → RDF (Turtle), deterministically.

**URI stability policy**: published concept URIs are never deleted or renamed. Labels may change; retired concepts carry `owl:deprecated true` + `skos:changeNote` and remain in the file.

**License**: [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0), matching the AGET framework.

**Authority note**: the authoritative vocabulary lives fleet-local in the AGET framework; this published copy is a one-way record (no inbound binding).
