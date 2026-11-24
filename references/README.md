# Citation records

BibTeX records for the publications listed in the root README, and the scope
rules of the collection they belong to.

This folder holds citation records only. The papers themselves live on Zenodo;
each file here carries the metadata needed to cite one of them.

## Naming

The filename is the Zenodo record ID, which is also the suffix of the DOI:

| File | DOI |
|---|---|
| `23310745.bib` | `10.5281/zenodo.23310745` |

## Using them

Reference the record by its file name, for example
`\bibliography{references/23310745}` in a LaTeX document.

## Adding a record

1. Export the record from Zenodo as BibTeX.
2. Save it as `<record-id>.bib`.
3. Add the paper to the table in the root README, same order.

When a work gains a new version, add the new record as a new file. Do not rewrite
an existing entry: a citation that resolved yesterday should resolve to the same
record tomorrow.

## What the collection accepts

Deposits are author-submitted work relevant to constrained, on-device, and
zero-telemetry AI:

- specifications
- conformance reports
- test vectors
- datasets
- benchmark results
- implementation notes

Acceptance is a curation decision, not peer review, conformance assessment, or
certification. Deposits are checked for scope and obvious misrepresentation, not
for technical correctness.

## Conditions

- Deposits must be the uploader's own work, or work they are authorized to
  deposit.
- A third party may not be described as conformant, certified, or endorsed
  without that party's written claim.
- Claims against GCAII-STD-0001 are recorded in the project registry. The
  community does not verify, approve, or endorse them.

## Removal

A deposit may be removed from the collection, without deleting the record
itself, if it falls outside the scope above, duplicates another deposit, or
misstates conformance or endorsement. Disagreement with the community's views is
not grounds for removal.

## Authority

The community page states the authoritative policy:
[zenodo.org/communities/gcaii](https://zenodo.org/communities/gcaii). This file
summarises it for readers of this folder. If the two differ, the community page
wins.

## Scope

These records describe the author's independent publications. They are not part
of GCAII-STD-0001 and are not normative.

Repository text is CC BY 4.0, as stated in the root README.
