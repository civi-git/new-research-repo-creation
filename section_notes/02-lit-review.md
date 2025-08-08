# Literature Review: AI Agents for Scientific Research

## Overview

The application of AI agents to scientific research represents a transformative paradigm shift from traditional human-driven discovery processes to autonomous or semi-autonomous AI systems capable of conducting end-to-end research workflows. This literature review examines recent advances in AI agents designed for scientific discovery, following CS197 methodology to identify key assumptions, innovations, and future directions.

## Core Research Question

**How can AI agents autonomously conduct scientific research, from hypothesis generation to experimental validation, and what are the fundamental assumptions that current approaches make about the nature of scientific discovery?**

## Key Papers Analysis

### 1. Robin: A Multi-Agent System for Automating Scientific Discovery (Ghareeb et al., 2025)

**Problem**: Scientific discovery requires iterative cycles of background research, hypothesis generation, experimentation, and data analysis, but no system had previously automated all stages in a unified workflow.

**Prior Assumptions**: Previous work assumed that individual components of scientific discovery could be automated separately, but full integration was not feasible; human oversight was necessary for meaningful scientific insights.

**Insight**: Multi-agent architecture integrating literature search agents with data analysis agents can achieve semi-autonomous scientific discovery by orchestrating specialized AI capabilities in a coordinated workflow.

**Technical Approach**: Robin uses multiple specialized agents (Crow for literature search, Falcon for molecular evaluation, Finch for data analysis) coordinated to propose hypotheses, design experiments, and interpret results. Applied to dry age-related macular degeneration research.

**Evaluation**: Successfully identified ripasudil as a novel therapeutic candidate for dAMD, validated through experimental work. All hypotheses, experimental plans, and analyses were AI-generated.

**Impact**: First demonstrated end-to-end AI-driven discovery with real-world validation, establishing proof-of-concept for autonomous scientific research systems.

### 2. The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery (Lu et al., 2024)

**Problem**: Creating AI agents capable of conducting scientific research and discovering new knowledge, moving beyond narrow task assistance to full research autonomy.

**Prior Assumptions**: Scientific research requires human creativity, intuition, and domain expertise that cannot be replicated by AI; automated systems could only assist with specific sub-tasks.

**Insight**: Large language models can perform the complete research cycle - idea generation, implementation, experimentation, analysis, and paper writing - when provided with appropriate frameworks and evaluation mechanisms.

**Technical Approach**: Integrated system that generates research ideas, writes code, executes experiments, visualizes results, writes papers, and conducts automated peer review. Applied to machine learning research domains.

**Evaluation**: Generated papers that exceed acceptance thresholds at top ML conferences according to automated reviewers. Cost-effective at ~$15 per paper.

**Impact**: Demonstrated feasibility of fully automated scientific workflows, though with acknowledged limitations in paper quality and evaluation reliability.

### 3. The AI Scientist-v2: Workshop-Level Automated Scientific Discovery (Yamada et al., 2025)

**Problem**: First-generation AI Scientist relied on human-authored code templates and lacked generalization across diverse research domains.

**Prior Assumptions**: Automated research systems required extensive human-provided scaffolding and domain-specific customization to function effectively.

**Insight**: Progressive agentic tree-search methodology with dedicated experiment manager agents can eliminate reliance on human templates while improving research quality and domain generalization.

**Technical Approach**: Enhanced architecture with experiment manager agent, tree-search methodology for exploration, and Vision-Language Model feedback loops for iterative refinement.

**Evaluation**: First AI-generated paper to pass peer review at ICLR workshop, achieving scores above human acceptance threshold.

**Impact**: Milestone achievement in AI-driven research validation through traditional academic peer review processes.

### 4. Agentic AI for Scientific Discovery: A Survey (Gridach et al., 2025)

**Problem**: Lack of comprehensive framework for understanding the landscape of agentic AI systems in scientific discovery across different domains.

**Prior Assumptions**: Agentic AI applications in science were domain-specific solutions without common underlying principles or evaluation frameworks.

**Insight**: Agentic AI systems share common capabilities (reasoning, planning, autonomous decision-making) that can be systematically categorized and evaluated across scientific domains.

**Technical Approach**: Comprehensive survey methodology categorizing existing systems, evaluation metrics, and implementation frameworks across chemistry, biology, and materials science.

**Evaluation**: Analysis of key evaluation metrics, datasets, and frameworks provides benchmarking foundation for the field.

**Impact**: Establishes taxonomies and evaluation standards for comparing agentic AI systems in scientific discovery.

### 5. BioDisco: Multi-Agent Hypothesis Generation (Ke et al., 2025)

**Problem**: Existing automated hypothesis generation methods struggle with novelty, evidence grounding, and systematic refinement processes.

**Prior Assumptions**: Hypothesis generation could rely primarily on literature synthesis without structured reasoning processes or systematic uncertainty quantification.

**Insight**: Dual-mode evidence systems (knowledge graphs + literature retrieval) combined with iterative feedback loops and temporal evaluation enable robust hypothesis generation.

**Technical Approach**: Multi-agent framework with planner, literature searcher, knowledge graph querier, scientist agent for integration, and critic for evaluation and refinement.

**Evaluation**: Superior novelty and significance compared to existing architectures through Bradley-Terry paired comparison model and human evaluation.

**Impact**: Demonstrates importance of systematic evidence integration and iterative refinement in AI-driven hypothesis generation.

## Cross-Cutting Themes and Assumptions

### Literature-Level Assumptions Identified:

1. **Sequential Process Assumption**: Most systems assume scientific discovery follows linear stages (literature review → hypothesis → experiment → analysis), but real research often involves complex feedback loops and iterative refinement.

2. **Domain Transferability Assumption**: Current systems assume that successful architectures in one domain (e.g., ML research) will transfer to other scientific fields without significant modification.

3. **Evaluation Validity Assumption**: Automated evaluation systems (AI reviewers, metrics) can reliably assess research quality and novelty, despite limited validation against human expert judgment.

4. **Integration Sufficiency Assumption**: Combining existing AI capabilities (LLMs, search, analysis) through multi-agent architectures is sufficient for scientific discovery, without need for fundamentally new AI capabilities.

5. **Human-AI Collaboration Assumption**: Most systems assume optimal workflows involve AI conducting intellectual work while humans perform physical experiments, rather than full end-to-end automation.

### Potential Bit Flips:

**Assumption**: Scientific discovery requires sequential, rational processes that can be systematically automated.

**Potential Flip**: Scientific breakthroughs often emerge from non-linear, serendipitous processes that resist systematic automation but could be enhanced through AI systems designed for creative exploration rather than systematic execution.

**Assumption**: Domain-specific knowledge is the primary bottleneck in scientific research automation.

**Potential Flip**: The primary bottleneck is not domain knowledge but the ability to identify and challenge fundamental assumptions across disciplinary boundaries.

## Research Gaps and Future Directions

1. **Assumption Validation**: Limited empirical testing of whether AI-identified assumptions and hypotheses match those that lead to significant scientific breakthroughs.

2. **Creative Discovery**: Current systems optimize for feasible, evidence-based research but may miss paradigm-shifting discoveries that challenge fundamental assumptions.

3. **Interdisciplinary Integration**: Most systems operate within single domains; cross-disciplinary discovery remains largely unexplored.

4. **Long-term Impact Assessment**: Lack of longitudinal studies on whether AI-generated research leads to meaningful scientific progress.

5. **Failure Mode Analysis**: Insufficient investigation of systematic biases and failure modes in AI-driven research processes.

## Synthesis

The field of AI agents for scientific research has rapidly evolved from proof-of-concept demonstrations to systems achieving peer-reviewed validation. The common thread across all approaches is the assumption that scientific discovery can be decomposed into automated sub-processes and coordinated through multi-agent architectures. However, this literature reveals a potential paradigm-level assumption: that scientific discovery is fundamentally a systematic, rational process rather than a creative, assumption-challenging endeavor.

Future research should explore whether AI systems designed to identify and flip fundamental assumptions - following the CS197 bit-flip methodology - might achieve more transformative scientific discoveries than current systematic approaches.

---
*Literature review completed using CS197 research methodology*
*Analysis covers 18+ papers from 2024-2025*
*Focus on identifying literature-level assumptions and potential bit flips*
