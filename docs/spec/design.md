# Design — Multi-Modal Evidence Review

> **Spec-Driven Development.** This document is the single source of truth for
> **HOW** the system is built. Single file for now; expected to split
> (evaluation methodology for images and transcripts first) as the architecture
> deepens — at which point this becomes an overview/index and area docs move
> under `docs/spec/design/`.
>
> Tracking: `cbeaulieu-gt/hackerrank-orchestrate-june26-prv#1`

## 1. Architecture overview

_TBD_

## 2. Data loading & path resolution

_TBD — CSV loaders; resolve `images/...` paths against `dataset/`._

## 3. Pipeline (staged gates)

_TBD — validate evidence (authenticity) → assess relevance/sufficiency → render verdict._

## 4. VLM interaction

_TBD — provider/model, structured output, retries, determinism._

## 5. Prompt design

_TBD_

## 6. Evaluation methodology

_TBD — expected first split point: image-evidence eval vs. transcript eval._

## 7. Operational analysis

_TBD — model calls, token usage, cost, latency, TPM/RPM, caching / batching / retry strategy._
