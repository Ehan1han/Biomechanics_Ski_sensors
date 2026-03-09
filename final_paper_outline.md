# Final Paper Outline

## Title

- Minimum Wearable Sensor Configuration for Estimating Combined Valgus-Plus-Rotation During Alpine Ski Turning

## Abstract

- State that ACL injury is a major problem in alpine skiing.
- Note that direct field-based injury-risk measurement is difficult.
- Summarize the gap between skiing ACL mechanism studies and reduced-sensor wearable studies.
- State that the paper focuses on a single turning-related proxy: combined valgus-plus-rotation exposure.
- Briefly describe the proposed reference-system and sensor-reduction study.
- End with the practical significance of understanding fidelity versus sensing burden.

## Introduction: Background and Previous Investigations

### 1. Clinical and Biomechanical Importance

- ACL injury is a major severe injury in both competitive and recreational alpine skiing.
- Skiing is biomechanically distinctive because skis, boots, and bindings create sport-specific loading pathways.
- Preventing skiing ACL injury requires skiing-specific rather than generic field-sport models.

### 2. Skiing ACL Mechanisms Relevant to Turning

- World Cup video studies identify slip-catch and related turning scenarios as major ACL mechanisms.
- These mechanisms repeatedly involve coupled knee valgus and tibia-femur rotation.
- Recreational carving-ski studies show that forward twisting mechanisms are also common outside elite racing.
- Explain why the paper is focused on turning/carving and not jump-landing mechanisms.

### 3. Why Use Proxies Instead of Direct Injury Prediction

- ACL rupture is a rare endpoint and cannot be directly reproduced or measured in field experiments.
- Skiing ACL research therefore depends on mechanism-based and model-based surrogate variables.
- The most defensible proxy for this paper is combined valgus-plus-rotation exposure because it is directly grounded in the skiing mechanism literature and is more plausibly recoverable from wearable kinematics than more ambitious force-line variables.

### 4. Wearable Sensing in Skiing

- Ski-racing biomechanics has often relied on rich multimodal systems and expert-focused study designs.
- Full-body IMU and IMU-plus-insole systems show that skiing kinematics and kinetics can be measured outdoors.
- Reduced-sensor studies show that sparse setups can detect turns and quantify motion quality.
- Placement-sensitive studies show that sensor location matters.
- However, these wearable studies do not directly address ACL-proxy reconstruction under sensor minimization.

### 5. Gap Statement

- The open question is not whether wearables can measure ski motion.
- The real gap is how much ACL-relevant proxy information is lost as sensor count is reduced.
- This motivates a reference-system study comparing reduced sensor subsets during on-snow carving turns.

## Proposed Research

### 1. Study Question and Aim

- How does reconstruction fidelity for combined valgus-plus-rotation exposure change as wearable sensor count is reduced during alpine ski turning?
- Use a rich wearable reference system, compare reduced sensor subsets against it, and characterize the tradeoff between biomechanical fidelity and sensing burden.

### 2. Target Proxy and Reference System

- Focus on one proxy, combined valgus-plus-rotation exposure, because it is the clearest turning-related ACL surrogate supported by the current literature.
- Estimate that proxy from a full-body 17-IMU suit plus bilateral plantar pressure insoles, used as a reference platform rather than direct ground truth for injury risk.

### 3. Participants, Protocol, and Reduced Configurations

- Recruit roughly 24 to 30 skiers across beginner, intermediate, and advanced levels, and collect turning data across more than one snow condition.
- Use a standardized carving-turn protocol with multiple runs per participant.
- Create reduced configurations by masking sensors from the full recorded trials; compare plausible sets such as boot-only, boots plus pelvis, and lower-limb-centered configurations.

### 4. Proxy Computation, Reconstruction, and Evaluation

- Segment turns from the reference system, compute the proxy for each turn, and use those values as the benchmark targets for reduced configurations.
- Start with simple, interpretable estimators based on turn-phase and segment-motion features.
- Evaluate reduced sets with turn-level error metrics and compare fidelity across skier groups and snow conditions.
- Present the result as a fidelity-versus-sensor-count relationship, using a Pareto-frontier framing to identify promising tradeoffs.

### 5. Limitations and Significance

- The target is a biomechanical surrogate, not true injury probability.
- Field data are noisy because snow, speed, and turn shape vary.
- Reduced configurations may generalize unevenly across skier skill levels.
- Proxy fidelity may degrade differently across snow conditions.
- The study’s value is to connect skiing ACL mechanism research with wearable-system design and identify lower-burden sensing strategies for ACL-oriented field monitoring.

## Conclusion

### 1. Main Claim

- Combined valgus-plus-rotation exposure is the clearest ACL-related turning proxy to study under sensor reduction with the current literature base.

### 2. Contribution of the Proposed Study

- The work frames sensor minimization as a biomechanical proxy-reconstruction problem rather than a general motion-quality problem.
- It connects injury-mechanism knowledge to deployable sensing design.

### 3. Future Directions

- Extend to additional skiing mechanisms after the turning-focused framework is established.
- Evaluate other derived loading variables once stronger wearable support exists.
- Test intervention or feedback applications after the sensing tradeoff is understood.

## Figures and Tables

### Table 1

- Compact literature synthesis table showing:
  ACL mechanism studies, wearable skiing studies, main outputs, and the unresolved gap.

### Table 2

- Proxy table centered on combined valgus-plus-rotation exposure:
  mechanistic rationale, reference-system estimate, reconstruction challenge, and evaluation target.

### Figure 1

![Figure 1. Conceptual pipeline for the proposed paper.](figures/figure1_pipeline.svg)

[Open Figure 1](figures/figure1_pipeline.svg)

### Figure 2

![Figure 2. Reference and candidate reduced sensor configurations.](figures/figure2_sensor_configurations.svg)

[Open Figure 2](figures/figure2_sensor_configurations.svg)
