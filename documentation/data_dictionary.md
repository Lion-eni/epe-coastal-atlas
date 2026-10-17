# Data Dictionary

## Purpose

This document defines the core fields proposed for the Epe Coastal Atlas inventory. Field names may be adapted to match the final dataset, but changes should be documented.

| Field | Type | Description |
|---|---|---|
| `record_id` | Text | Unique identifier for a candidate record |
| `name` | Text | Reported name of the location or feature |
| `category` | Text | Feature type, such as fish market, landing site, jetty or aquaculture facility |
| `latitude` | Decimal | Latitude in decimal degrees, where available |
| `longitude` | Decimal | Longitude in decimal degrees, where available |
| `source_name` | Text | Name of the source used |
| `source_url` | Text | Source URL, where available |
| `evidence_tier` | Text | Evidence classification assigned using documented criteria |
| `verification_status` | Text | Current coordinate and evidence verification status |
| `coordinate_method` | Text | How coordinates were obtained or estimated |
| `positional_uncertainty` | Text/Number | Known or estimated positional uncertainty |
| `date_accessed` | Date | Date the source was accessed |
| `notes` | Text | Relevant limitations, duplicate concerns or validation notes |

## Verification Status Guidance

Suggested values:

- `Documented — coordinate needed`
- `Coordinates available — not independently verified`
- `Approximate location — verify before analysis`
- `Mapped source — coordinate available`
- `Field verified`
- `Duplicate candidate — review required`

These values must reflect the evidence actually available. Do not assign `Field verified` without a documented field verification process.

## Evidence Classification

Evidence tiers should be assigned using an explicit, documented rubric. A published scientific paper, an authoritative government record, an OpenStreetMap feature and an approximate coordinate are not interchangeable forms of evidence.

A record may have coordinates while still requiring verification. Coordinate availability and source reliability should be stored separately.

## Coordinate Reference Systems

Original coordinates should be retained in their documented source reference system. Latitude and longitude in decimal degrees normally correspond to a geographic coordinate reference system such as WGS 84 (EPSG:4326), but this must be checked rather than assumed.

Projected coordinates should record the relevant CRS and be created from validated source coordinates.

## Duplicate Handling

Records that may describe the same physical location should be flagged for review. Similar names or nearby coordinates alone do not prove that two records are duplicates.

## Data Integrity

Never replace missing coordinates with invented values. Record unresolved fields as missing and document the next verification step.
