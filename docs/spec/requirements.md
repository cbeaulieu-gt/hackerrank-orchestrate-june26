# Requirements — Multi-Modal Evidence Review

> **Spec-Driven Development.** This document is the single source of truth for
> **WHAT** the system does. Sections below are scaffolding — content is authored
> and evolved during the research + brainstorm phase.
>
> Tracking: `cbeaulieu-gt/hackerrank-orchestrate-june26-prv#1`

## 1. Problem & scope

_TBD_

## 2. Trust model

_TBD — `claim_object` and `user_history` authoritative; `user_claim` transcript and image(s) suspect; images are the primary source of truth but only after clearing authenticity + relevance gates._

## 3. Inputs

_TBD — `user_id`, `image_paths`, `user_claim`, `claim_object`; plus `user_history.csv` and `evidence_requirements.csv`._

## 4. Output contract (14 fields, fixed order)

_TBD_

## 5. Field semantics & allowed values

_TBD — per-field meaning and the enumerated allowed values._

## 6. Decision rules

_TBD — `claim_status` (supported / contradicted / not_enough_information); `evidence_standard_met`; `valid_image`; `severity`; `risk_flags`; `supporting_image_ids`._

## 7. Acceptance criteria

_TBD — conformance metrics measured against the labeled sample set (`dataset/sample_claims.csv`)._
