# Serendipity Affordance Feature Repository

This repository accompanies the paper [Serendipity in Recommender Systems Beyond the Algorithm: A Feature Repository and Experimental Design](https://pure.itu.dk/ws/portalfiles/portal/98207011/paper4.pdf).

It catalogs affordance features that may help recommender systems support serendipitous encounters. The repository follows the paper's three-part structure:

- [Content](features/content/): item data, metadata, controlled vocabularies, user-generated content, and multimedia.
- [User interface](features/user-interface/): visible or audible presentation choices that influence what users notice, inspect, and follow.
- [Information access](features/information-access/): recommendation, search, and browsing mechanisms that shape how users reach items.

The feature pages are intended to be practical research objects: each page gives a short definition, the relevant serendipity sub-affordances, implementation notes, and linked example snippets.

## Repository Map

```text
.
|-- assets/
|   `-- snippets/                 # Screenshot snippets named by source and feature mapping
|-- data/
|   `-- taxonomy.yml              # Machine-readable version of the feature taxonomy
|-- docs/
|   |-- FEATURE_TEMPLATE.md
|   `-- REPOSITORY_PLAN.md
|-- features/
|   |-- content/
|   |-- user-interface/
|   `-- information-access/
|       |-- recommendation/
|       |-- search/
|       `-- browsing/
|-- CONTRIBUTING.md
|-- LICENSE
`-- README.md
```

## Feature Index

### Content

| Code | Feature | Page |
| --- | --- | --- |
| C1 | Core metadata | [features/content/c1-core-metadata.md](features/content/c1-core-metadata.md) |
| C2 | Controlled vocabulary | [features/content/c2-controlled-vocabulary.md](features/content/c2-controlled-vocabulary.md) |
| C3 | User-generated content | [features/content/c3-user-generated-content.md](features/content/c3-user-generated-content.md) |
| C4 | Multimedia | [features/content/c4-multimedia.md](features/content/c4-multimedia.md) |

### User Interface

| Code | Feature | Page |
| --- | --- | --- |
| U1 | Metadata | [features/user-interface/u1-metadata.md](features/user-interface/u1-metadata.md) |
| U2 | User-generated content | [features/user-interface/u2-user-generated-content.md](features/user-interface/u2-user-generated-content.md) |
| U3 | Multimedia | [features/user-interface/u3-multimedia.md](features/user-interface/u3-multimedia.md) |
| U4 | Global navigation | [features/user-interface/u4-global-navigation.md](features/user-interface/u4-global-navigation.md) |
| U5 | Presentation structure | [features/user-interface/u5-presentation-structure.md](features/user-interface/u5-presentation-structure.md) |
| U6 | Headers | [features/user-interface/u6-headers.md](features/user-interface/u6-headers.md) |
| U7 | Explanations | [features/user-interface/u7-explanations.md](features/user-interface/u7-explanations.md) |
| U8 | Emphasis | [features/user-interface/u8-emphasis.md](features/user-interface/u8-emphasis.md) |
| U9 | Pop-up | [features/user-interface/u9-pop-up.md](features/user-interface/u9-pop-up.md) |

### Information Access

| Code | Feature | Page |
| --- | --- | --- |
| R1 | Personalized recommendation | [features/information-access/recommendation/r1-personalized.md](features/information-access/recommendation/r1-personalized.md) |
| R2 | Non-personalized recommendation | [features/information-access/recommendation/r2-non-personalized.md](features/information-access/recommendation/r2-non-personalized.md) |
| R3 | Curated recommendation | [features/information-access/recommendation/r3-curated.md](features/information-access/recommendation/r3-curated.md) |
| R4 | Item-to-item recommendation | [features/information-access/recommendation/r4-item-to-item.md](features/information-access/recommendation/r4-item-to-item.md) |
| R5 | User-to-user recommendation | [features/information-access/recommendation/r5-user-to-user.md](features/information-access/recommendation/r5-user-to-user.md) |
| S1 | Search engine | [features/information-access/search/s1-search-engine.md](features/information-access/search/s1-search-engine.md) |
| S2 | Auto-completion | [features/information-access/search/s2-auto-completion.md](features/information-access/search/s2-auto-completion.md) |
| B1 | Hyperlinks | [features/information-access/browsing/b1-hyperlinks.md](features/information-access/browsing/b1-hyperlinks.md) |
| B2 | Breadcrumb trails | [features/information-access/browsing/b2-breadcrumb-trails.md](features/information-access/browsing/b2-breadcrumb-trails.md) |
| B3 | Collections | [features/information-access/browsing/b3-collections.md](features/information-access/browsing/b3-collections.md) |
| B4 | User profiles | [features/information-access/browsing/b4-user-profiles.md](features/information-access/browsing/b4-user-profiles.md) |

## How To Use This Repository

- Use the feature pages to identify candidate design manipulations for a recommender-system study.
- Use `data/taxonomy.yml` when you need a structured source for scripts, website generation, or cross-repository reuse.
- Add example screenshots to `assets/snippets/`, using the source-plus-feature naming pattern, and list them on the relevant feature page.
- Keep examples grounded in observable interface features, not inferred algorithmic behavior unless the source explicitly documents it.

## Source

The taxonomy and descriptions are based on Section 3 and Table 2 of the accompanying paper. The paper frames serendipity as a user experience shaped by content, interface, and information-access features, not only by recommendation algorithms.
