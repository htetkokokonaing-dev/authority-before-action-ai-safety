# Authority Before Action

**A Conditional Failure-Chain Framework for Tool-Using AI Safety**  
Author: **Htet Ko Ko Naing**  
ORCID: [0009-0000-6140-0495](https://orcid.org/0009-0000-6140-0495)  
Version: **Zenodo Final Version, June 2026**

This repository supports the paper **_Authority Before Action: A Conditional Failure-Chain Framework for Tool-Using AI Safety_**.

The paper develops a conceptual and operational framework for analyzing authority failures in tool-using AI systems. It argues that prompt injection and related adversarial failures become operationally dangerous when untrusted content receives an inappropriate authority role and crosses a consequential boundary such as output release, tool execution, memory update, workflow action, or policy-relevant signal.

## Status

This repository is a **companion project repository** for the Zenodo paper.

It provides:

- the final paper files;
- extracted figures from the paper;
- benchmark schema and scoring templates for future supplementary implementation;
- citation metadata;
- licensing information.

It does **not** report executed benchmark results, deployment-safety results, or real-world incident prevalence.

## Zenodo DOI

Zenodo DOI: **[10.5281/zenodo.20541041](https://doi.org/10.5281/zenodo.20541041)**
## Indexing / Archive Links

- Zenodo DOI: https://doi.org/10.5281/zenodo.20541041
- PhilPapers / PhilArchive: https://philpapers.org/rec/NAIABA-2
- GitHub companion repository: https://github.com/htetkokokonaing-dev/authority-before-action-ai-safety
## Paper

The final paper is available in the [`paper/`](paper/) folder:

- [`Authority_Before_Action_Zenodo_Final_June2026.pdf`](paper/Authority_Before_Action_Zenodo_Final_June2026.pdf)
- [`Authority_Before_Action_Zenodo_Final_June2026.docx`](paper/Authority_Before_Action_Zenodo_Final_June2026.docx)

## Core idea

The framework treats prompt injection as a subtype of a broader class: **authority-assignment failures**.

A failure becomes operationally dangerous when:

1. untrusted content is granted an inappropriate authority role;
2. that mistaken authority influences instruction, evidence, permission, policy, memory, user intent, or action;
3. the mistaken authority crosses a declared commitment boundary;
4. usable signal, sufficient time, effective authority, and valid policy are not jointly available before commitment.

## Main concepts

- Authority assignment
- Authority-role separation
- Commitment boundary
- Release/action gate
- Signal-Time-Authority plus policy control condition
- Authority-Boundary Benchmark v0.1
- Incident coding by authority role, boundary crossed, and STA bottleneck

## Repository structure

```text
authority-before-action/
  README.md
  CITATION.cff
  LICENSE
  RELEASE_NOTES.md
  paper/
    Authority_Before_Action_Zenodo_Final_June2026.pdf
    Authority_Before_Action_Zenodo_Final_June2026.docx
  figures/
    figure-1-conditional-failure-chain.png
    figure-2-release-action-gate.png
    README.md
  benchmark/
    README.md
    case_schema.csv
    scoring_template.csv
  docs/
    project_description.md
```

## Benchmark status

The paper specifies **Authority-Boundary Benchmark v0.1** as a controlled synthetic benchmark design with five task families:

1. RAG Injection
2. Tool-use Boundary
3. Evidence Integrity
4. Memory Safety
5. Workflow Escalation

The benchmark materials in this repository are currently **schema and template files only**. They are included to make future implementation easier. They should not be interpreted as completed empirical results.

## Related prior work

This paper extends and integrates the author's prior DOI-linked framework work:

- **Strategic Robustness in Artificial Intelligence: A Conditional Failure-Chain Framework for Adversarial Robustness**  
  https://doi.org/10.5281/zenodo.20289236

- **Signal-Time-Authority Runtime Oversight: A Pre-Commitment Controllability Framework**  
  https://doi.org/10.5281/zenodo.19980763

- **Graduated STA Control: Authority Governors and Runtime Deployment Architecture**  
  https://doi.org/10.5281/zenodo.19984352

- **Governed Hazard Predicates and Assurance Cases for STA Runtime Oversight**  
  https://doi.org/10.5281/zenodo.19984993

- **STA Conditional Commitment Architecture for Output-Mediated and Multi-Agent AI Systems**  
  https://doi.org/10.5281/zenodo.20063055

- **Signal-Time-Authority Public Release Series Collection**  
  https://doi.org/10.5281/zenodo.19985331

## Suggested citation

Please cite the Zenodo record:

```text
Naing, H. K. K. (2026). Authority Before Action: A Conditional Failure-Chain Framework for Tool-Using AI Safety. Zenodo. https://doi.org/10.5281/zenodo.20541041
```

A machine-readable citation file is provided in [`CITATION.cff`](CITATION.cff).

## License

Unless otherwise noted, the text, figures, and repository materials are released under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**. See [`LICENSE`](LICENSE).

## Contact

Htet Ko Ko Naing  
Independent Researcher  
Correspondence: <nanglieng17@gmail.com>
