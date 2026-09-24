# Stanford Multi-omics Hackathon 2026 Track 6

## MoTrPAC × LINCS Perturbation Challenge

*Can we use drug and gene perturbations to steer a simulated cell toward — or away from — an exercise-like molecular state?*

### Challenge

Match selected MoTrPAC exercise-response signatures against LINCS L1000 and approved gene-set libraries, then use the ranked perturbations in a game where players guide a simulated cell over several turns. LLM- and MCP-enabled workflows may explain each perturbation and generate evidence briefs for the resulting trajectories.

### Data

Selected human acute-exercise or rat endurance-training signatures, precomputed drug and gene perturbation effects from [LINCS L1000](https://lincsproject.org/LINCS/tools/workflows/find-the-best-place-to-obtain-the-lincs-l1000-data), approved gene-set libraries, and source metadata.

### Potential Outputs

- Reproducible signature-matching pipeline
- Ranked perturbation library
- Playable web prototype with trajectory visualization and evidence briefs

> [!TIP]
> Teams should use a fixed target signature and precomputed perturbation effects. Realistic mechanistic simulation and real-time model training are outside scope.

> [!IMPORTANT]
> Simulated trajectories are exploratory and do not establish biological causality or therapeutic efficacy. Evidence briefs must preserve citations, distinguish retrieved evidence from generated interpretation, state uncertainty, and undergo human review before public use.
