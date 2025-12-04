# METHODOLOGY

## Analytical Frameworks and Approaches

This document describes the rigorous analytical methodologies used in the **Global Crisis 2025-2050** research project to ensure quality, transparency, and reproducibility of findings.

---

## Core Analytical Methods

### 1. System Dynamics Modeling

**Purpose**: Model complex feedback loops and cascading effects in interconnected crisis systems.

**Methodology**:
- **Stock and Flow Analysis**: Quantifying accumulation and movement of resources, people, capital, and information
- **Feedback Loops**: Identifying reinforcing loops (acceleration) and balancing loops (stabilization)
- **Time Delays**: Accounting for lags between cause and effect (critical for understanding cascades)
- **Non-linear Relationships**: Capturing disproportionate effects and tipping points

**Applications**:
- Climate-economy interactions
- Technology adoption and diffusion
- Conflict escalation and de-escalation
- Migration system dynamics
- Resource consumption patterns

**Tools**: Vensim, Stella, Anylogic, custom Python models

**Validation**: Comparison with historical data, expert review, sensitivity analysis

---

### 2. Network Analysis (Social Network Analysis - SNA)

**Purpose**: Map interconnections between crisis elements and identify critical nodes and pathways.

**Methodology**:
- **Node Identification**: Key actors, institutions, systems, and crisis elements
- **Connection Mapping**: Direct causal links, indirect influences, feedback mechanisms
- **Centrality Analysis**: Identifying most influential nodes using multiple measures
  - **Betweenness**: Nodes bridging different parts of the network
  - **Closeness**: Nodes with shortest average distance to others
  - **Degree**: Nodes with most direct connections
  - **PageRank**: Nodes receiving influence from other influential nodes
- **Cascade Modeling**: How disruptions propagate through the network
- **Community Detection**: Identifying clusters of related crises

**Applications**:
- Crisis interconnection mapping
- Identifying intervention leverage points
- Assessing network vulnerability
- Understanding information flows
- Mapping power structures and relationships

**Tools**: Gephi, Cytoscape, NetworkX, custom Python/R scripts

**Visualization**: Network graphs, adjacency matrices, flow diagrams

---

### 3. Agent-Based Modeling (ABM)

**Purpose**: Simulate emergent system behavior from individual actor decisions and interactions.

**Methodology**:
- **Agent Definition**: Heterogeneous actors (individuals, organizations, governments) with different goals and constraints
- **Behavior Rules**: Decision-making logic for each agent type
- **Interaction Rules**: How agents influence each other
- **Environment**: System state that agents perceive and respond to
- **Emergence**: Complex system behavior arising from simple individual rules
- **Stochasticity**: Random variation in outcomes

**Applications**:
- Scenario modeling (divergent futures)
- Policy intervention testing
- Crisis escalation/de-escalation pathways
- Population behavior and migration
- Technological adoption patterns

**Tools**: NetLogo, MASON, Python (mesa library)

**Validation**: Calibration to historical data, sensitivity analysis, expert review

---

### 4. Causal Inference

**Purpose**: Identify true causal relationships (not just correlations) between crisis elements.

**Methodology**:
- **Causal Diagrams** (DAGs): Visual representation of causal relationships
- **Randomized Controlled Trials**: When possible, random assignment to treatment/control
- **Quasi-Experimental Methods**: Using natural experiments and regression discontinuity
- **Structural Equation Modeling**: Testing complex causal chains
- **Instrumental Variables**: Using exogenous variation to identify causal effects
- **Confounding Analysis**: Identifying and controlling for alternative explanations

**Applications**:
- Understanding whether A causes B (not just related)
- Quantifying causal strength
- Identifying causal mechanisms
- Predicting effects of interventions

**Tools**: DAGitty, R (causaleffect), Python (DoWhy)

**Key References**: Judea Pearl, "The Book of Why"; Miguel Hernan, "Causal Inference: The Mixtape"

---

### 5. Scenario Planning and Analysis

**Purpose**: Explore multiple consistent future pathways based on current conditions and choices.

**Methodology**:
- **Trend Analysis**: Identifying and extrapolating current trends
- **Uncertainty Mapping**: Cataloging key uncertainties affecting outcomes
  - Known knowns (facts)
  - Known unknowns (identified uncertainties)
  - Unknown unknowns (unidentified risks/opportunities)
- **Scenario Axes**: Selecting 2-3 most critical uncertainties for scenario structure
- **Scenario Development**: Creating internally consistent narratives for each scenario
- **Backcasting**: Working backward from scenarios to identify necessary conditions
- **Plausibility Testing**: Evaluating whether scenarios are realistic

**The Three Scenarios**:
1. **Star Trek**: Coordinated global transformation (25% probability)
2. **Equilibrium Terror**: Authoritarian stability (35% probability)
3. **Mad Max**: Systemic collapse (40% probability)

**Tools**: Custom scenario frameworks, Monte Carlo simulation, expert panels

**Validation**: Expert review, stakeholder feedback, internal consistency checking

---

### 6. Quantitative Risk Assessment

**Purpose**: Combine probability and impact to systematically assess and prioritize risks.

**Methodology**:
- **Probability Estimation**: Using historical frequency, expert judgment, and modeling
- **Impact Assessment**: Quantifying potential consequences on multiple dimensions
- **Risk Matrices**: Combining probability and impact to prioritize risks
- **Sensitivity Analysis**: Testing how parameter changes affect risk rankings
- **Monte Carlo Simulation**: Running thousands of scenarios with random variations
- **Uncertainty Quantification**: Communicating confidence levels and ranges

**Risk Formula**: Risk = Probability × Impact × Vulnerability

**Applications**:
- Prioritizing interventions
- Resource allocation
- Early warning systems
- Scenario probability assessment

**Tools**: Python (scipy, numpy), @Risk, custom models

---

### 7. Comparative Case Study Analysis

**Purpose**: Deep analysis of specific crises to understand mechanisms and drivers.

**Methodology**:
- **Case Selection**: Choosing cases for theoretical relevance and information richness
- **Within-Case Analysis**: Detailed examination of each case's dynamics
- **Cross-Case Comparison**: Identifying similarities, differences, and patterns
- **Process Tracing**: Documenting causal sequences and mechanisms
- **Counterfactual Analysis**: What would have happened with different conditions

**Structure**:
1. Background and context
2. Crisis dynamics and escalation
3. Key actors and their interests
4. Critical junctures and turning points
5. Lessons and generalizations

**Tools**: Qualitative data analysis software (Atlas.ti, NVivo), process tracing templates

---

## Data Sources and Quality

### Primary Data Categories

| Category | Sources | Confidence | Update Frequency |
|----------|---------|------------|------------------|
| **Conflict Data** | UCDP, ACLED, Armed Conflict Location & Event Data | 90%+ | Monthly |
| **Economic Data** | IMF, World Bank, OECD, national statistics | 90%+ | Quarterly |
| **Climate Data** | NOAA, NASA, IPCC, national weather agencies | 85-90% | Daily/Monthly |
| **Technology Data** | Company reports, industry analyses, research papers | 70-80% | Quarterly |
| **Social Data** | Surveys, polling organizations, academic studies | 60-80% | Annual/Quarterly |
| **Migration Data** | UN, national immigration agencies, NGO reports | 70-85% | Annual |

### Data Validation Process

1. **Source Verification**: Check credibility and methodology of data provider
2. **Cross-Checking**: Verify against multiple independent sources
3. **Outlier Analysis**: Identify and investigate unusual values
4. **Temporal Consistency**: Check for discontinuities or suspicious changes
5. **Expert Review**: Have domain experts evaluate for plausibility
6. **Documentation**: Record data source, collection date, methodology, limitations

### Confidence Levels

| Level | Range | Criteria | Examples |
|-------|-------|----------|----------|
| **High** | 90%+ | Current data from reliable sources, validated independently | Conflict death counts, inequality statistics |
| **Medium** | 70-90% | Well-established trends, multiple sources, some uncertainty | Climate projections, economic trends |
| **Lower** | 50-70% | Speculative, model-dependent, limited validation | Long-term scenario outcomes, tech timelines |

---

## Addressing Uncertainty

### Uncertainty Categories

**Epistemic Uncertainty** (Can be reduced with research):
- Incomplete data
- Model structure uncertainty
- Parameter uncertainty
- Limited historical precedent

**Aleatory Uncertainty** (Inherent randomness):
- Random variation
- Stochastic events
- Human agency and unpredictable choices
- Unknown unknowns

### Uncertainty Communication

1. **Explicit Ranges**: Provide low/medium/high estimates
2. **Confidence Intervals**: 95% or 90% confidence ranges
3. **Sensitivity Analysis**: Show which parameters matter most
4. **Scenario Bounds**: Range from optimistic to pessimistic scenarios
5. **Qualitative Hedging**: Language reflecting uncertainty ("likely," "might," "could")

---

## Peer Review and Validation

### Internal Review Process

1. **Author Review**: Self-check for errors and clarity
2. **Editor Review**: Check organization, consistency, citations
3. **Expert Review**: Domain specialists evaluate content
4. **Methodology Review**: Statistical and analytical approach assessment
5. **Fact-Check Review**: Verification of key claims and data

### External Validation

1. **Community Feedback**: Soliciting input from broader stakeholders
2. **Stakeholder Interviews**: Discussing findings with key actors
3. **Comparative Analysis**: Benchmarking against other research
4. **Longitudinal Validation**: Testing predictions against subsequent events

### Transparency

- All assumptions documented
- Limitations clearly stated
- Alternative interpretations noted
- Uncertainty clearly communicated
- Raw data and models available for reproducibility

---

## Limitations and Caveats

### Fundamental Limitations

1. **Predictive Uncertainty**: Complex systems are inherently unpredictable
2. **Model Dependency**: Results depend on model structure and assumptions
3. **Data Gaps**: Missing information for conflict-affected regions, autocracies
4. **Feedback Loops**: Non-linear effects and tipping points difficult to predict
5. **Human Agency**: Individual choices and leadership can alter trajectories
6. **Black Swan Events**: Low-probability, high-impact events by definition unpredictable
7. **Value Judgments**: Some conclusions reflect values, not just facts

### Methodological Limitations

- **Quantification Bias**: Tendency to overweight quantifiable factors
- **Expert Bias**: Experts may have systematic blind spots
- **Western Bias**: Research may reflect Western perspectives
- **Time Lag**: Data collection and analysis create time lags
- **Scope Constraints**: Cannot analyze every possible factor or region

### Data Limitations

- **Reporting Gaps**: Underreporting in conflict-affected regions
- **Definitional Issues**: Different countries define indicators differently
- **Historical Bias**: Limited data for unprecedented current conditions
- **Spatial Bias**: Better data for developed countries
- **Temporal Gaps**: Missing data for specific time periods

---

## Ethical Considerations

### Research Ethics

1. **Potential Harm**: Consider how research findings might be misused
2. **Representation**: Ensure affected communities are fairly represented
3. **Transparency**: Clearly communicate methods and limitations
4. **Attribution**: Properly credit sources and contributors
5. **Neutrality**: Distinguish analysis from advocacy

### Data Ethics

1. **Privacy**: Protect individual privacy and confidentiality
2. **Informed Consent**: Ensure proper permission for data use
3. **Equity**: Avoid perpetuating discrimination or bias
4. **Transparency**: Clear about data sources and usage
5. **Correction**: Mechanisms for correcting inaccuracies

---

## Reproducibility

### Requirements for Reproducibility

1. **Clear Methodology**: Detailed description of analytical approaches
2. **Data Availability**: Raw data available (subject to privacy constraints)
3. **Code Availability**: Analysis code available with documentation
4. **Parameter Documentation**: All assumptions and parameters clearly stated
5. **Sufficient Detail**: Enough detail for independent replication

### Reproducibility Commitment

- Publish code alongside analysis (GitHub)
- Document all data sources and collection methods
- Provide parameter files and model specifications
- Include sensitivity analysis showing parameter impacts
- Invite and facilitate independent verification

---

## Quality Assurance Framework

### Standards

| Dimension | Standard | Measurement |
|-----------|----------|-------------|
| **Accuracy** | ≥90% on verifiable claims | Fact-checking against multiple sources |
| **Completeness** | Address major aspects of topic | Scope checklist review |
| **Clarity** | Accessible to target audience | Readability analysis |
| **Consistency** | No contradictions within analysis | Logical consistency check |
| **Currency** | Using latest available data | Data freshness review |
| **Credibility** | Proper citations and sources | Citation completeness |

### Continuous Improvement

1. **Feedback Loops**: Community feedback on errors and gaps
2. **Version Control**: Documenting changes and improvements
3. **Regular Updates**: Periodic review and updating of analysis
4. **Post-Publication Review**: Learning from real-world developments
5. **Correction Mechanisms**: Process for correcting errors

---

## Contributing Your Methodology Improvements

We welcome suggestions for improving analytical approaches:

1. **Document Your Critique**: Clearly explain limitations or alternatives
2. **Propose Solution**: Suggest specific improvement or alternative method
3. **Provide Evidence**: Show why your approach is better
4. **Discuss Tradeoffs**: Acknowledge limitations of your approach
5. **Open Discussion**: Be open to feedback and refinement

See [CONTRIBUTING.md](CONTRIBUTING.md) for process details.

---

## References and Further Reading

### Key Methodological References

- **System Dynamics**: Forrester, J.W. (1969). Urban Dynamics. MIT Press.
- **Network Analysis**: Newman, M. (2010). Networks: An Introduction. Oxford University Press.
- **Agent-Based Modeling**: Gilbert, N. & Troitzsch, K. (2005). Simulation for the Social Scientist.
- **Causal Inference**: Pearl, J. (2009). Causality: Models, Reasoning and Inference.
- **Scenario Planning**: Schwartz, P. (1996). The Art of the Long View.

### Domain-Specific References

- **Climate Science**: IPCC Assessment Reports
- **Conflict Studies**: Human Security Report Project
- **Economic Analysis**: World Economic Forum Global Risk Reports
- **Technology**: MIT Technology Review, OpenAI, DeepMind publications

---

## Questions About Methodology?

- **Issues**: Use GitHub Issues for methodology questions
- **Discussions**: Use GitHub Discussions for broader conversations
- **Contributions**: Propose methodology improvements via pull requests

---

**Last Updated**: December 2025  
**Version**: 1.0  
**Maintained By**: @mag00s

This methodology framework will be updated as the project evolves and new approaches are incorporated.
