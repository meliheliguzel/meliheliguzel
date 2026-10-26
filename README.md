# Genomic data quality & reproducible pipelines

I have a background in molecular biology and genetics, combined with software engineering. I build focused, well-tested tools that catch structural and quality problems in sequencing data before they reach downstream analysis pipelines—and I share the engineering work in public as I go.

---

## Shipped

* **[seq-qc-probe](https://github.com/meliheliguzel/seq-qc-probe)** — Open-source FASTQ integrity and quality-control checker. Engineered in Python (`uv`), containerized with Docker, and validated via GitHub Actions CI against synthetic error fixtures (`pytest`).

## Building now

- [x] **FASTQ validation CLI (`v0.1.0`)** — Structural invariants & Phred distributions ([`seq-qc-probe`](https://github.com/meliheliguzel/seq-qc-probe))
- [ ] **VCF 4.2 validation module** — Strict header schema and column-level invariant checks
- [ ] **Containerized Nextflow variant-calling pipeline** — Benchmarked against GIAB (Genome in a Bottle) truth sets
- [ ] **Single-cell QC workflow** — Reproducible preprocessing built on the `scverse` ecosystem
- [ ] **`stats-note`** — Concise, code-backed notebooks on the statistical mechanics behind RNA-seq and single-cell analysis

---

## What I use, and where you can see it

| Area | Tools & Standards | Public Evidence |
| :--- | :--- | :--- |
| **Python tooling** | `uv`, `pytest`, strict typing, GitHub Actions CI | [`seq-qc-probe`](https://github.com/meliheliguzel/seq-qc-probe) |
| **Containers & Env** | Docker, deterministic dependency locking | [`seq-qc-probe`](https://github.com/meliheliguzel/seq-qc-probe) |
| **Genomics & QC** | FASTQ/VCF invariants, Phred statistics, position/read metrics | [`seq-qc-probe`](https://github.com/meliheliguzel/seq-qc-probe) |

**Active R&D & Expanding into:** Nextflow (DSL2), `nf-core` modular standards, R / Bioconductor.

---

## How I work

* **Fixed-scope engagements** with clearly written technical boundaries and limitations.
* **Evidence-backed claims:** Every parser, filter, or metric is backed by unit tests, synthetic error fixtures, or benchmarks in public repositories.
* **Plain-language reporting:** Clear, actionable diagnostic summaries without black-box ambiguity.

## Work with me

I take on a small number of fixed-scope data-quality reviews and tooling engagements for early-stage biotech teams and academic labs—focusing on pre-pipeline FASTQ/VCF integrity audits, custom validation scripts, and reproducible QC reporting.

📫 **Contact & Links:** [aselvi.com](https://aselvi.com) | [ORCID](https://orcid.org/0009-0006-4251-7683) | [LinkedIn](https://www.linkedin.com/in/melih-eliguzel/)
