# Serendipity Affordance Feature Repository

This repository accompanies the paper [Serendipity in Recommender Systems Beyond the Algorithm: A Feature Repository and Experimental Design](https://pure.itu.dk/ws/portalfiles/portal/98207011/paper4.pdf).

It catalogs affordance features that may help recommender systems support serendipitous encounters. The repository can be browsed in two complementary ways:

- [Browse by feature](features/FEATURES.md): start from content, user-interface, or information-access features and see which serendipity affordances they may stimulate.
- [Browse by serendipity affordance](affordances/AFFORDANCES.md): start from a serendipity affordance and see which features and examples may stimulate it.

The repository also contains example screenshots from recommender-system interfaces. Snippet filenames encode the place where the example was found and the feature tags visible in the example, such as `IMDB-C1-Core-metadata-U1-Metadata-B1-Hyperlinks.png`.

## Repository Structure

```text
.
|-- affordances/                  # Reverse browse tree by serendipity affordance
|   |-- AFFORDANCES.md
|   |-- diversifiability/
|   |-- sensoriability/
|   `-- traversability/
|-- assets/
|   `-- snippets/                 # Screenshot snippets named by source and feature mapping
|-- data/
|   `-- taxonomy.yml              # Machine-readable version of the taxonomy
|-- docs/
|   |-- FEATURE_TEMPLATE.md
|   `-- REPOSITORY_PLAN.md
|-- features/                     # Browse tree by feature category
|   |-- FEATURES.md
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

## How To Use This Repository

- Use [features/FEATURES.md](features/FEATURES.md) to identify concrete design features for analysis or experimental manipulation.
- Use [affordances/AFFORDANCES.md](affordances/AFFORDANCES.md) to reason from a desired serendipity affordance back to feature candidates.
- Use [data/taxonomy.yml](data/taxonomy.yml) when you need a structured source for scripts, website generation, or cross-repository reuse.
- Add example screenshots to `assets/snippets/`, using the source-plus-feature naming pattern, and list them on the relevant feature and affordance pages.

## Scope

The taxonomy follows the paper's three feature categories: content, user interface, and information access. The affordance browse tree follows the paper's serendipity sub-affordance structure: diversifiability, traversability, and sensoriability.

This is a living repository: examples should be grounded in observable interface evidence, documented system behavior, or clearly marked inference.
