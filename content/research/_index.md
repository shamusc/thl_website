---
title: Research
date: 2026-06-19
type: landing

sections:
  - block: markdown
    content:
      title: Research
      subtitle: From microbiome observations to testable biocontrol hypotheses
      text: |
        Turtle House Labs focuses on the problem of moving from plant microbiome observations to testable biocontrol hypotheses. In many studies, microbial taxa are identified as differentially abundant between healthy and diseased plants, but the path from association to useful intervention is often unclear. The goal of this work is to make that translational step more systematic.
    design:
      columns: '1'
      spacing:
        padding: ['80px', '0', '20px', '0']

  - block: markdown
    content:
      title: The problem
      text: |
        Plant-associated microbial communities may contain organisms that suppress disease, compete with pathogens, prime host defenses, or stabilize healthy community states. However, observational sequencing studies are often difficult to translate into candidate biocontrol organisms.

        Key challenges include:

        - Disease and healthy plants differ for many reasons besides protective microbes.
        - Relative abundance data can be misleading because microbiome data are compositional.
        - Taxonomic resolution varies by sequencing method.
        - Many organisms are poorly characterized or not present in reference databases.
        - Candidate taxa require follow-up validation before they can be treated as functional biocontrol agents.

        Sequencing data alone does not prove biocontrol function. The framework described below is about improving candidate discovery and experimental design, not claiming that correlation is proof of causation.
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']

  - block: markdown
    content:
      title: The framework
      text: |
        We treat biocontrol candidate discovery as a pipeline that connects sampling, sequencing, statistical analysis, ecological reasoning, and validation:

        1. **Define the disease system and sampling design.** Identify the host, the pathogen, the relevant tissues, and the conditions under which protective effects could plausibly be observed.
        2. **Collect healthy and diseased plant tissue under interpretable conditions.** Pay close attention to confounders such as cultivar, location, season, and disease stage.
        3. **Use appropriate sequencing methods for the organisms of interest.** Match the assay (amplicon, shotgun metagenomics, ITS, etc.) to the biological question and known limitations.
        4. **Analyze community differences with attention to confounders.** Use compositionally aware methods and report uncertainty honestly.
        5. **Prioritize candidates** using abundance patterns, recurrence across samples or studies, ecological plausibility, and association with disease state.
        6. **Design verification experiments.** Co-culture, in planta, or controlled-environment assays appropriate to the candidate and the host.
        7. **Move promising candidates toward controlled and field-relevant validation.** Field-relevance is defined backwards from what would be needed for practical agricultural use.

        The scientific value is in making the disease/biocontrol analysis stage more systematic, reproducible, and easier to iterate.
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']

  - block: markdown
    content:
      title: Why the phyllosphere?
      text: |
        The phyllosphere is the above-ground plant surface environment, including leaves and other aerial tissues. It is directly exposed to pathogens, weather, agricultural treatments, and environmental variation. Because many foliar diseases begin or develop on aerial plant surfaces, the phyllosphere is a natural place to search for microbial interactions relevant to disease suppression.

        Phyllosphere communities are also tractable to sample non-destructively and at scale, which makes them well suited to the kind of comparative, candidate-discovery work described above.
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']

  - block: markdown
    content:
      title: Computational approach
      text: |
        Our work draws on bioinformatics, microbiome analysis, ecological reasoning, and AI-assisted scientific workflows. We do not treat AI as a substitute for biological validation. Instead, it is used as a tool for literature synthesis, workflow design, candidate prioritization, and reasoning about complex data.

        Microbial community data are difficult to interpret because of compositionality, sampling variation, host plant effects, environmental confounding, disease-stage effects, incomplete taxonomic resolution, poorly characterized organisms, and the gap between statistical association and causal protection. Honest interpretation requires keeping these limitations visible at every step.
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']

  - block: markdown
    content:
      title: Translational goal
      text: |
        The goal is to help researchers and growers move more efficiently from complex microbial data toward experimentally testable disease-management hypotheses. Concretely, that means producing analysis frameworks, prioritized candidate lists, and study designs that are credible enough to justify the next experiment.
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '80px', '0']
---
