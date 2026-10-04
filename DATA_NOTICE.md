# Data notice

This repository contains privacy-minimized samples derived from public business-profile data returned by an audited Actor run.

- Direct contact fields, street addresses, long business descriptions, images, reviewer names, review text, and owner replies are omitted.
- The three output files are field-preserving projections of records in dataset `JII2EV4hr0fjTeSgR`, produced by run `z8lykAkMmj9cVLdON` on build `0.3.5`.
- The audited run used `profiles_only` and `maxReviewsPerProfile: 0`, so it produced no individual review rows.
- Ratings, counts, certificate flags, verification labels, and dates are source-reported observations. They are not independently verified facts.
- `trustScore`, benchmark percentiles, match confidence, and change signals are analytical outputs. They are not official platform scores and are not proof of fake, fraudulent, manipulated, or authentic reviews.
- ProvenExpert, Trusted Shops, eKomi, and Google are trademarks of their respective owners. This independent project is not affiliated with, endorsed by, or sponsored by those companies.

Before collecting or retaining data, confirm that your use complies with applicable laws, platform terms, privacy obligations, and your own retention policy. Source availability and fields can change.

## Listing update on September 30, 2026

The Store title, description and search metadata were checked against the owned Actor and synchronized with this repository. This documentation update does not alter executable code, input or output schemas, recorded test outputs, artifact hashes, billing or runtime builds. Existing examples retain their original dates and validation limits. A public listing is not evidence of successful output, network acceptance or an achieved search ranking.

## Maintenance evidence on October 4, 2026

[`maintenance-verification-2026-10-04.json`](maintenance-verification-2026-10-04.json) records offline validation of the Actor maintenance: branch identity, explicit group boundaries, conservative legacy-baseline comparisons and incomplete benchmark exclusion. It contains aggregate check counts and code hashes, without synthetic source fixtures, customer inputs or new source output. The 39 author tests and six final independent check groups do not prove live source accessibility or customer impact. Separately, public `latest` build `0.3.14` / `hEfIts2TtAI7VnFED` compiled successfully and its server source hashes matched the reviewed release package. Current editable dependencies were preserved without pin edits. No new runtime/source run was opened.

Automatic entity keys migrate; explicit business-group hashes stay stable. Preserve profile IDs/URLs and original timestamps in retained baselines. Missing or contradictory legacy identity and incomplete prior snapshots are held incomplete with null deltas. A changed source URL with a retained ID can also hold a comparison; the code does not assume it is an alias. Existing samples, schemas and their historical provenance are unchanged.
