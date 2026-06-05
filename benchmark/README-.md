# Authority-Boundary Benchmark v0.1

This folder is reserved for the benchmark specification and future supplementary materials associated with the paper:

**Authority Before Action: A Conditional Failure-Chain Framework for Tool-Using AI Safety**

## Status

The benchmark files in this repository are currently **templates and schemas only**.

They do **not** report executed benchmark results, model performance, real-world incident prevalence, or deployment safety.

## Planned benchmark families

The paper specifies five controlled synthetic task families:

1. RAG Injection
2. Tool-use Boundary
3. Evidence Integrity
4. Memory Safety
5. Workflow Escalation

## Intended future files

Future benchmark releases may include:

- full case set;
- adversarial and benign case variants;
- scoring rubric;
- evaluator sheet;
- simulated tool markers;
- run harness notes;
- summary formulas;
- condition comparison table.

## Current files

- `case_schema.csv` — column schema for future benchmark cases.
- `scoring_template.csv` — column schema for future scoring rows.

## Important limitation

The benchmark is included as a reproducible evaluation specification. It should not be interpreted as completed empirical validation until executed results are explicitly released.
